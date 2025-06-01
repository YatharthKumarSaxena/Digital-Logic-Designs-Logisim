# 🔢 Welcome to the Day-1 Digital Logic Circuits!
> **I'm the README.md file of this folder, here to guide you step-by-step!** 🚀  
This was my **Day-1 journey** into the world of digital logic, where I started implementing logic gates using real ICs on breadboard and later simulated the exact circuits on Logisim for better visualization.

---

## 🧠 What I Learned on Day-1

On this very first day, I began with basic gate constructions and then moved toward a more complex circuit:
- ✅ **Basic Logic Gates**: AND, OR, NOT using respective ICs.
- ✅ **Full Subtractor** using **only NAND gates**, with a focus on **gate-level optimization**.

I didn’t try building multiple logic variations. The focus was clearly on how a **Full Subtractor** can be built **only using NAND gates**, that too with the **minimum number of gates** possible.

---

## 🧪 Optimization Insight

> Full Subtractor using only **NAND gates** typically takes ~20 gates if implemented naively.  
Through logical reduction and deeper gate manipulation, I implemented the full subtractor using just **9 NAND gates**, effectively:
- Reducing total gate count by **more than 50%**
- Saving **2 whole ICs** (each IC has 4 gates)

🎯 **The goal was to minimize hardware usage**, a key mindset in digital circuit design.

---

## ⚠️ Important Note

In this experiment, we were **not provided with a NOT gate IC (IC7404)**.  
Hence, I used the **NAND gate as a NOT gate** (by shorting its inputs), a standard and smart workaround in digital logic.

---


## 📁 Folder Structure

This folder contains a total of **3 files**:

- 🖼️ **3 screenshots**: showing the NAND-based Full Subtractor and Full Subtractor Implemented by AND,OR,XOR and NOT Gates  
- 🔌 **1 `.circ` file**: Logisim circuit containing both designs

---

## 💻 Simulation Instructions

> You can **run the `.circ` file directly in Logisim**.  
It allows you to toggle input bits and observe the real-time behavior of the logic circuits including the **NAND-based Full Subtractor**.

This digital version replicates the hardware we created using:
- 🧱 **IC7400** for NAND
- 🧱 **IC7408** for AND
- 🧱 **IC7432** for OR
- 🧱 **IC7486** for XOR (only if required in other days)

---

## 🎯 **Final Takeaway**

This day laid the foundation for:
✔️ Realizing digital logic using actual ICs  
✔️ Thinking in terms of **gate economy and IC economy**  
✔️ Using **NAND gates as universal gates** effectively, even when hardware constraints (like unavailability of NOT gate IC) exist.

---

