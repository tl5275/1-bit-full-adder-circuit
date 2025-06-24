# 🔢 1-Bit Full Adder in Logisim

This project implements a **1-bit full adder** using **basic logic gates** in [Logisim Evolution](https://github.com/reds-heig/logisim-evolution), a graphical tool for designing and simulating digital logic circuits.

---

## 🧠 What Is a 1-Bit Full Adder?

A **1-bit full adder** is a combinational digital circuit that performs the addition of three input bits:
- `A` – First input bit
- `B` – Second input bit
- `Cin` – Carry-in (from previous bit)

### It produces two outputs:
- `Sum` – The resulting sum bit
- `Cout` – Carry-out to the next bit

---

## 📊 Truth Table

| A | B | Cin | Sum | Cout |
|---|---|-----|-----|------|
| 0 | 0 | 0   |  0  |  0   |
| 0 | 0 | 1   |  1  |  0   |
| 0 | 1 | 0   |  1  |  0   |
| 0 | 1 | 1   |  0  |  1   |
| 1 | 0 | 0   |  1  |  0   |
| 1 | 0 | 1   |  0  |  1   |
| 1 | 1 | 0   |  0  |  1   |
| 1 | 1 | 1   |  1  |  1   |

---

## 🧮 Boolean Expressions

- **Sum** = `A ⊕ B ⊕ Cin`
- **Cout** = `(A ∧ B) ∨ (B ∧ Cin) ∨ (A ∧ Cin)`

---

## 🛠️ How to Simulate

1. Open **Logisim Evolution**.
2. Create a new circuit.
3. Add the following components:
   - 3 input pins: `A`, `B`, and `Cin`
   - 2 XOR gates
   - 3 AND gates
   - 2 OR gates
   - 2 output pins: `Sum`, `Cout`
4. Wire them according to the boolean expressions above.
5. Simulate by toggling input values.

---

## 📂 Files Included

- `1bit_full_adder.circ` – Logisim Evolution circuit file
- `README.md` – Project documentation

---

## 📸 Screenshot

> ![1-bit full adder circuit](https://github.com/user-attachments/assets/6a9dfd5b-5af1-421b-a0c1-fcdebc0ee2e8)

---

## 📚 References

- [Logisim Evolution GitHub](https://github.com/reds-heig/logisim-evolution)
- Digital Logic Design textbooks

---

## 📜 License

This project is open-source and free to use under the [MIT License](LICENSE).

---
