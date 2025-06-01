# 🔄 Welcome to the Finite State Machine (Edge Detector) – Day-10 Folder!
> **I'm the README.md file of this folder, here to guide you step-by-step!** 🚀  
This folder focuses on implementing a **Finite State Machine (FSM)** designed to **detect positive edges** using both simulation and real digital hardware components.

---

## 🧠 What I Learned in the Day-10 Folder

In this experiment, I made the transition from simulation to hardware-based FSM implementation. The objective was to design a **minimal Finite State Machine** capable of detecting a **positive edge transition** using **JK flip-flops** and **NAND gates**, following a **Mealy Machine** approach.

Through this, I learned not only FSM theory but also how to realize it using **real hardware** and **Logisim simulation**.

---

## 🧪 Technical Highlights

### ⚙️ Hardware & Simulation Details

- 🔌 **Digital IC Trainer Kit (ML-444T)**
- 📦 **NAND Gate IC – 7400**
- 📦 **Dual JK Flip-Flop IC – 74107**
- ⚡ **Breadboard, Connecting Wires, and Manual Push Buttons**
- 💾 **Logisim `.circ` file** with both:
  - ✅ JK Flip-Flop Simulation
  - ✅ Final FSM Circuit

> ⚠️ Clock was **manually applied** using push buttons, **not** taken from trainer kit (e.g., 1Hz or 1kHz), to avoid bounce and timing mismatch.

---

## 🔍 Design Summary

- 🧠 **FSM Type**: **Mealy Machine**  
  > Because the **output depends on both current state and input**.

- 🎯 **Purpose**: Detect a **positive edge** in the input signal  
- 🔁 **States**:  
  - `S0`: Waiting for rising edge  
  - `S1`: Edge detected, output active

- 🔧 **Circuit Elements**:
  - ✅ **Master-Slave JK Flip-Flop** to prevent **race-around condition**
  - ✅ **Active-Low Clear (RESET)** for noise immunity and industry preference
  - ✅ **Negative Edge Triggered** flip-flops for stable sequential response

---

## 📁 Folder Structure

This folder contains:

- 🧾 `README.md`  
  > You’re reading it now – complete documentation of the experiment.

- 🖼️ `JK_FlipFlop_Simulation.png`  
  > A simulation screenshot showing the working of Master-Slave JK Flip-Flop.

- 🖼️ `FSM_Positive_Edge_Detector.png`  
  > Screenshot of the final FSM that detects rising edges.

- 🧠 `FSM_Edge_Detector.circ`  
  > Logisim simulation file including both:
  - JK Flip-Flop (Master-Slave)
  - Final FSM circuit

---

## 🧪 Hardware Setup Steps

1. Connect **JK Flip-Flops** (74107) in **Master-Slave configuration**.
2. Use **NAND Gates** to derive required state transition and output logic.
3. Manually apply **clock pulses** using push buttons.
4. Use **LEDs** to observe output pulse on edge detection.
5. Use **Active-Low Clear** to initialize/reset states.

> ✅ Always debounce your input signal to avoid spurious transitions.

---

## ⚖️ Moore vs Mealy Machine – What We Used?

| Feature             | Moore Machine            | Mealy Machine ✅       |
|---------------------|--------------------------|------------------------|
| Output depends on   | Only current state       | Current state + Input |
| Output changes      | After state transition   | Immediately with input|
| Our FSM model       | ❌ Not applicable         | ✅ Implemented         |

✔️ **Mealy Machine** was the correct choice because the output needed to respond immediately to input changes, which is crucial in edge detection.

---

## 🎯 **Final Takeaway**

From this hardware-based FSM implementation, I walked away with:

✔️ Strong understanding of **sequential logic & FSM modeling**  
✔️ Difference between **Moore vs Mealy Machines**  
✔️ Design of **positive edge detectors** using minimal logic  
✔️ Experience using **Master-Slave JK Flip-Flops**  
✔️ Realization of **timing-sensitive circuits** using **manual clock control**  
✔️ Enhanced skill in **translating state diagrams to working circuits**

---

