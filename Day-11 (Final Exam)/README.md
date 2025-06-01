# 📘 Welcome to the PYQ & Final Exam Circuit Practice – Day-11 Folder!
> **I'm the README.md file of this folder, here to guide you step-by-step!** 🚀  
This final folder is a blend of **PYQ-based practice circuits** and the **actual problem statement I solved during my final Digital Logic exam**, focusing on MUX and Flip-Flop based shift-register designs.

---

## 🧠 What I Learned in the D11 Folder

In this final stage, I explored both **classic digital logic conversions** and **complex conditional shifting operations** using **MUX** and **D Flip-Flops**. I also practiced creating **manual MUX designs** from logic gates and understood real-world applications of **master-slave flip-flops** with clean triggering and resets.

---

## 🧪 Technical Highlights

### 📋 PYQ Circuits Practiced

- 🔄 **Binary to Gray Code Converter**
- 🔢 **Binary to BCD Converter**

✅ Both circuits are:
- Included in the `.circ` simulation file
- Supported by individual **screenshots**

---

### 🧪 Final Exam Problem (Simulated Design)

I received the following logic design task in my Digital Logic Design final exam:

> 🧠 **Design a conditional shift register** using **MUX and D Flip-Flops**, with control inputs:
>
> | Control Input | Operation                       |
> |---------------|----------------------------------|
> | `00`          | Parallel Load                    |
> | `01`          | Circular Right Shift by 2 bits   |
> | `10`          | Serial Right Shift by 1 bit      |
> | `11`          | Circular Left Shift by 2 bits    |

### 🔧 My Implementation:

- 🔀 Used **4×1 MUX** (joined using 2×1 MUX blocks) to select operations
- 🔄 Manually designed **2×1 MUX** using **AND, OR, and NOT gates**
- ⛓️ Connected 4×1 MUX outputs to **D Flip-Flops** in **Master-Slave Configuration**
- 🧼 Integrated **Active-Low Clear** for reset logic
- 🕹️ Applied **Negative Edge Triggering** for stable operation

> ⚠️ Note: This circuit was designed **only in simulation**, not on hardware.

---

## 🧩 Why Active-Low Clear and Negative Edge Trigger?

| Feature              | Why It Was Used                                                                 |
|----------------------|----------------------------------------------------------------------------------|
| 🧼 **Active-Low Clear**  | ✅ More noise-immune and **industry standard** reset design                     |
| ⬇️ **Negative Edge Trigger** | ✅ Ensures stable state changes; **avoids race conditions** in sequential circuits |

---

## 📁 Folder Structure

This folder contains:

- 🧾 `README.md`  
  > The file you are reading now — complete documentation of the final exam logic and PYQ practice.

- 🖼️ `Binary_to_Gray_Converter.png`  
  > Simulation screenshot of the classic code conversion circuit.

- 🖼️ `Binary_to_BCD_Converter.png`  
  > Screenshot of the BCD conversion logic.

- 🧠 `PYQ_Circuit.circ`  
  > Logisim file that includes:
  - Binary to Gray Code Converter  
  - Binary to BCD Converter  
  > *(Note: Final Exam Circuit was designed but not included in this file.)*

---

## 🎯 **Final Takeaway**

This folder marks the **culmination of my Digital Logic Design journey**. Here's what I gained:

✔️ Practical experience solving **PYQ-based digital circuits**  
✔️ Deep understanding of **MUX-based conditional shift operations**  
✔️ Capability to build **custom MUX circuits** using basic gates  
✔️ Mastery over **D Flip-Flop logic**, especially in **Master-Slave form**  
✔️ Confidence to handle **edge-sensitive sequential circuits** with correct triggering and resets  
✔️ Ability to **simulate exam-grade problems** independently in Logisim

---

