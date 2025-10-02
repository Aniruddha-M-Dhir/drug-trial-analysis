# Drug Testing – Venn Analysis & Visualization

This Python project analyzes drug trial results across **three drugs (A, B, C)** using the **inclusion–exclusion principle** and visualizes the overlaps with a **3-set Venn diagram**.  
It also identifies the **best** or **worst** performing drug (or overlap) based on user input.

---

## 📂 Project Structure
3 Drug Testing
README.md

---

## 🔹 Features
- Accepts user inputs for drug trial counts:
  - `|A|, |B|, |C|, |A∩B|, |A∩C|, |B∩C|, |A ∪ B ∪ C|`
- Calculates the **triple overlap** `|A ∩ B ∩ C|`
- Performs a **sanity check** to warn about inconsistent inputs
- Reports **best** or **worst** performers (max/min positives)
- Plots a **3-set Venn diagram** with `matplotlib-venn`

---

## 🧮 Formula Used
The triple overlap is computed using **inclusion–exclusion**:
|A ∩ B ∩ C| = |A ∪ B ∪ C| − (|A| + |B| + |C|) + (|A∩B| + |A∩C| + |B∩C|)

---
