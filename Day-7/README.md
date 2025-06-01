# 🔁 Welcome to the Bitwise Shifter and Sequential Circuits (Day-7 Folder)!
> **I'm the README.md file of this folder, here to guide you step-by-step!** 🚀  
This folder marks a significant milestone — the **beginning of Sequential Circuit design** using **D Flip-Flops**, after exploring combinational circuits in earlier folders.

---

## 🧠 What I Learned in the Day-7 Folder

In this experiment, I stepped into the world of **Sequential Circuits**, where current outputs depend not just on current inputs, but also on **previous states**.  
We were tasked to **design and simulate an 8-bit shifter** with **three select lines** to perform various operations.

### 🧮 Supported Operations via Select Lines (Binary Encoded):
| Select | Operation                       |
|--------|----------------------------------|
| `000`  | No Shift                         |
| `001`  | Circular Shift Left by 1-bit     |
| `010`  | Circular Shift Left by 2-bits    |
| `011`  | Circular Shift Right by 1-bit    |
| `100`  | Circular Shift Right by 2-bits   |
| `101`  | Serial Left Shift by 1-bit       |
| `110`  | Serial Right Shift by 1-bit      |
| `111`  | Parallel Load                    |

🧩 Inputs like `111` are used to represent binary (e.g., 7 = `111`) in select lines.

---

## 🧪 Technical Highlights

- 🔄 Built a custom **D Flip-Flop** using **Master-Slave Configuration** to avoid race-around conditions.
- 🔧 Used **MUX-based design**:
  - Designed **2×1 MUX** from scratch
  - Created **4×1 MUX** using multiple 2×1 MUXes
  - Built **8×1 MUX** in two ways:
    - Using **modular 2×1 and 4×1 MUXes**
    - Using **built-in 8×1 MUX** for performance

> 🧠 **Insight**:  
> Modular design promotes clarity and scalability but causes higher **propagation delay**.  
> Built-in MUXes offer better speed but reduced design transparency.

---

## 📁 Folder Structure

This folder contains:

- 🖼️ **Screenshots** of:
  - 2×1 MUX
  - 4×1 MUX
  - 8×1 MUX (both modular & built-in)
  - Final 8-bit Shifter
- 📂 **`shifter.circ`** file:
  > Contains all MUXes, D Flip-Flop, and the full 8-bit Shifter simulation

---

## 🧪 Simulation Instructions

> Open the `.circ` file using **Logisim**.

Inside, you’ll find:
- The complete **shifter circuit**
- All **MUX components**
- Custom **D Flip-Flop design**

Try toggling the **select lines** (S2, S1, S0) to test each operation as described above. Observe how input bits are shifted and preserved using **sequential logic**.

---

## 🎯 **Final Takeaway**

This experiment helped me understand:
✔️ The foundation of **sequential logic** using flip-flops  
✔️ How to simulate time-dependent behavior like shifts and memory  
✔️ The importance of **MUX design and circuit hierarchy**  
✔️ Tradeoffs between **modular vs built-in** components  
✔️ How shifting and loading operations interact with **bit-level data flow**

---

