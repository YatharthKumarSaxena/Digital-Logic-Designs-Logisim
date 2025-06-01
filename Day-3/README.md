# 🔢 Welcome to the Day-3 Digital Logic Circuits!
> **I'm the README.md file of this folder, here to guide you step-by-step!** 🚀  
This day focused on using the **provided 4x1 Dual MUX IC** to implement a logic function based on specific minterms using smart gate-level selection.

---

## 🧠 What I Learned on Day-3

The main goal was to use a **4x1 Multiplexer (MUX)** to implement a function with minterms:

```
F(w, x, y, z) = Σ(1, 2, 4, 7, 8, 9, 10, 11)
```

But with a **strategic optimization**:

- 🧩 We chose `w` and `x` as **select lines**  
- ⚙️ Inputs `y` and `z` were directly used as **data inputs**
- 🧠 This selection helped us **reduce the number of required logic gates**

---

## 🧪 Optimization Insight

- We used an **XOR IC** to reduce logical complexity.
- Another input line’s inversion was derived **using XOR's property**:  
  ```
  A ⊕ 1 = A̅
  ```

This trick allowed us to **simulate NOT logic without using a NOT gate**.

> Total number of gates used was **minimal** due to proper variable mapping and leveraging XOR properties.

---

## 🔌 Hardware Used

- 🔲 **4x1 Dual MUX IC** (e.g., IC 74153)
- 🧠 **XOR IC** (e.g., IC 7486)
- ⚡ No dedicated NOT IC was provided, so inversion was handled using logic tricks

---

## 📁 Folder Structure

This folder contains a total of **4 files**:

- 🖼️ **3 screenshots**: showcasing the hardware-equivalent circuit in Logisim  
- 🔌 **1 `.circ` file**: Logisim implementation of the 4x1 MUX-based function

---

## 💻 Simulation Instructions

> Open the `.circ` file using **Logisim**, and test the circuit by toggling values of `w`, `x`, `y`, `z`.  
You'll observe that the logic function with the given minterms is correctly implemented through proper **select line configuration and input data mapping**.

---

## 🎯 **Final Takeaway**

From this circuit, I learned:
✔️ The power of **MUX as a function generator**  
✔️ How to map variables to **minimize external gate usage**  
✔️ How to simulate NOT using **XOR properties**  
✔️ Real-world application of IC constraints and component choices

---

