# 🧮 Welcome to the BCD Adder Simulation (Day-6 Folder)!
> **I'm the README.md file of this folder, here to guide you step-by-step!** 🚀  
This folder contains the simulation of a **BCD (Binary-Coded Decimal) Adder** circuit implemented in **Logisim**.

---

## 🧠 What I Learned in the Basics Folder

In this experiment, I designed and simulated a **BCD Adder** by building on concepts from previous experiments:

- 🔄 Reused components like **Half Adder** and **Full Adder** from [Day-5](../Day-5/)
- 🧱 Designed a **Parallel Adder**
- 🧮 Built the BCD Adder by adjusting the output for binary values exceeding 9

Through this, I solidified my understanding of **decimal-binary conversions**, **carry corrections**, and how **BCD operations differ from binary arithmetic**.

---

## 💻 Simulation Insights

This was a **simulation-only** experiment using **Logisim**.  
The BCD Adder was built by chaining together adders and then conditionally adjusting output using the **"add 6"** rule when the sum exceeded 9.

> A key point:  
> ✅ The circuit handles values **only up to 19**.  
> ❗This is because:
> - Each BCD input is limited to 0–9.
> - So, the maximum sum (9 + 9 + carry) = **19**
> - Beyond this, the input is no longer valid in BCD format.

---

## 📁 Folder Structure

This folder contains:

- 🖼️ **Screenshots** showing the internal working of the Parallel Adder and BCD Adder
- 📂 **`.circ` file** with a complete Logisim simulation of the BCD Adder

---

## 🧪 Simulation Instructions

> Open the `.circ` file using **Logisim**.

Inside, you’ll find:
- A **Parallel Adder** to sum two 4-bit binary numbers  
- A logic block that **adds 6** when necessary to adjust the result to valid BCD  
- You can try inputs like 8 + 9, 7 + 7, or 9 + 9 + 1 (carry-in) to see how the circuit handles values up to 19

---

## 🎯 **Final Takeaway**

This experiment taught me how:
✔️ BCD arithmetic needs adjustment logic beyond basic binary addition  
✔️ Simple Full Adder and Parallel Adder units can scale up to decimal systems  
✔️ Input constraints define circuit boundaries — in this case, valid up to 19  
✔️ Reusability of previous circuit blocks can save time and maintain modularity

---
