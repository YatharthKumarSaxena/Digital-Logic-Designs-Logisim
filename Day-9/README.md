# 🔁 Welcome to the Sequence Generator Design (Day-9 Folder)!
> **I'm the README.md file of this folder, here to guide you step-by-step!** 🚀  
This folder focuses on building a **3-bit Binary Sequence Generator** using flip-flops and decoders—all simulated in **Logisim**.

---

## 🧠 What I Learned in the Day-9 Folder

In this experiment, the key focus was on designing a **custom sequence generator** using a **3-bit binary counter** and a **3x8 decoder**.  
This design helped bridge the understanding between simple counters and **controlled output logic systems**.

---

## 🧪 Technical Highlights

### 🔢 Core Circuit Components

- 🧮 **3-bit Binary Counter**
  - Built using **T Flip-Flops** designed in **Master-Slave architecture**
  - Ensures **race-around conditions** are eliminated
  - Clocked using a **Negative Edge Trigger**

- 🧩 **3x8 Decoder**
  - Converts 3-bit binary counter outputs to one-hot encoded signals
  - Integral for generating specific **custom sequences**

- 🎯 **Sequence Generator**
  - Utilizes decoder outputs to **activate user-defined output patterns**
  - Core logic to represent **state-dependent digital systems**

---

## ⚠️ Key Signal Practices Followed

- **Active-Low Clear (`CLR̅`)**:  
  ✔️ Offers higher **noise immunity**  
  ✔️ Matches real-world digital IC behavior

- **Negative-Edge Triggered Clock**:  
  ✔️ Avoids glitches due to signal rise-time instability  
  ✔️ Ensures proper timing with synchronous logic  
  ✔️ Common industry standard in modern digital systems

> 💡 These choices simulate real-world **hardware logic behavior** accurately and enhance circuit reliability.

---

## 📁 Folder Structure

This folder contains:

- 🔁 `Sequence Generator.circ`  
  > The main Logisim simulation file that includes:
  > - ✅ Master-Slave T Flip-Flop design  
  > - ✅ 3-bit Binary Counter  
  > - ✅ 3x8 Decoder  
  > - ✅ Final Sequence Generator Circuit

There are **no extra screenshots**, as everything is fully embedded and viewable in the `.circ` simulation.

---

## 🧪 Simulation Instructions

> Open `Sequence Generator.circ` in **Logisim**.

Here’s what you’ll explore:
- The **binary counter’s progression**
- The **decoder activating** respective output lines
- The **final sequence generator** output changing with each clock pulse

> 💡 Try modifying the output logic on the decoder to experiment with different sequence patterns.

---

## 🎯 **Final Takeaway**

Through this experiment, I understood:
✔️ How to construct **binary sequence generators** using counters and decoders  
✔️ The practical importance of **edge-triggering** and **active-low signals**  
✔️ How to implement **finite state patterns** from simple flip-flop-based counters  
✔️ Real-time insights into **synchronous sequence logic**

---

