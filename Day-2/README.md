# 🔢 Welcome to the Day-2 Digital Logic Circuits!
> **I'm the README.md file of this folder, here to guide you step-by-step!** 🚀  
This day revolved around the **design and implementation of Multiplexers (MUX)** — starting from scratch using only NAND gates.

---

## 🧠 What I Learned on Day-2

The core focus today was on understanding how **Multiplexers work internally**, not just relying on built-in MUX blocks. Here's what I implemented:

- ✅ **2x1 Multiplexer** using **only NAND gates**
- ✅ **4x1 Multiplexer** constructed using multiple 2x1 MUXes (built from NAND gates)

This practice helped me realize how even a standard MUX can be broken down into basic gates, and that **NAND gates alone are sufficient** for implementing complex combinational logic.

---

## 🧪 Optimization Insight

- Any **AND-OR-based MUX logic** can be **translated into NAND-only logic**
- Since NOT and AND can both be derived from NANDs, we can build a MUX using:
  - **Universal Gate Principle**: NAND is functionally complete
  - **Composability**: Build higher-order MUX (4x1) from multiple 2x1 units

> In this way, I constructed a **4x1 MUX** purely out of the basic building block: the **2x1 NAND-based MUX**.

---

## ⚠️ Important Note

> While capturing screenshots from Logisim, some circuits (like 4x1 MUX) may appear as **black MUX blocks** instead of gate-level detail.  
Please note — I have not used built-in MUX components.  
These blocks are **composed from individual NAND gates**, and you can verify that by **double-clicking or opening the `.circ` file** in Logisim.

---

## 📁 Folder Structure

This folder contains a total of **3 files**:

- 🖼️ **2 screenshots**: showing the NAND-based 2x1 and 4x1 MUX circuits  
- 🔌 **1 `.circ` file**: Logisim circuit containing both designs

---

## 💻 Simulation Instructions

> You can **open the `.circ` file in Logisim** and toggle select lines and input values to test the MUX logic.  
The internals of both 2x1 and 4x1 MUX can be explored to verify that all logic was manually built using only NAND gates.

---

## 🎯 **Final Takeaway**

This day strengthened my understanding of:
✔️ **Hierarchical circuit building**: 4x1 from 2x1  
✔️ **NAND-only digital logic design**  
✔️ Visualizing complex logic from primitive gates  
✔️ Efficient MUX implementation using optimized logic breakdown

---

