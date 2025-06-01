# 🧠 Welcome to the Day-8: 3-Decade BCD Counter Design Project!
> **I'm the README.md file of this folder, here to guide you step-by-step!** 🚀  

---

## 📚 **Table of Contents**
- 📖 Introduction
- 🛠️ Apparatus Used
- 📂 Folder Structure
- 🧪 Experiment Summary
- 🧠 Key Learnings
- 🎯 Final Takeaway

---

## 📖 **Introduction**
In this Day-8 experiment, I was tasked to **design and simulate a 3-decade BCD counter** using **Logisim**. This circuit required building **T Flip-Flops** using **Master-Slave architecture** to avoid race-around conditions and then combining them into a **3-decade counter**, where each decade counts from 0 to 9 — like in real-world digital clocks and calculators.

This experiment was an important transition point where I solidified my understanding of sequential digital design.

---

## 🛠️ **Components Used**
- 🧩 **T Flip-Flop** — Negative-Edge Triggered With Active Low Clear
- ⚙️ **Logisim Software** — for circuit design and simulation
---

## 📂 **Folder Structure**
The folder contains a total of **2 items**:
- 🖼️ **3 Screenshots**: Demonstrating step-by-step circuit development and simulation of the 3-decade BCD counter.
- 🧮 **`3 Decade Counter.circ`**: The complete Logisim file for simulating the entire counter logic.

You can open the `.circ` file in Logisim to test and visualize the working of the full 3-decade counter system.

---

## 🧪 **Experiment Summary**
Here’s how the entire system was built and tested:

- 🔁 A **T Flip-Flop** was designed using the **Master-Slave architecture** to eliminate race-around conditions common in toggle-based sequential circuits.
- 🧷 The **Clear signal** was configured as **Active-Low**, which is both an industry-standard and improves noise immunity.
- 🕓 A **Negative-edge clock** was chosen over a positive-edge clock, as most digital sequential circuits are triggered on the falling edge for stability.
- 🔢 Using these T Flip-Flops, a **single-decade counter (0–9)** was built and then replicated **three times**, chained together to create a full **3-decade BCD counter**.

---

## 🧠 **Key Learnings**
- Practical implementation of **Master-Slave T Flip-Flops** in sequential circuits.
- Industry insight into **Active-Low clears** and **Negative-edge triggering**.
- Realized how **decade counters can be cascaded** to build multi-digit counters — exactly like what’s used in digital clocks, elevators, and microcontrollers.
- Understood the logical depth and timing constraints in building **modular counters**.

---

## 🎯 **Final Takeaway**
> This Day-8 experiment helped me dive into **modular counter construction** using a chain of **3-decade BCD counters**, reinforcing concepts like **race condition handling**, **edge triggering**, and **sequential data propagation**.  
It truly bridged the gap between theory and practical design, preparing me for more complex digital systems in the future.

---
