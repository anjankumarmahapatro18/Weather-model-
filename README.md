# Weather Modeling (Quadratic) – SE Exp-1

This project implements a simple *weather modeling system* using a quadratic equation:  

\[
T(t) = a \cdot t^2 + b \cdot t + c
\]

Where:  
- *T(t)* → Predicted temperature  
- *t* → Time (hours/days)  
- *a, b, c* → Model coefficients  

---

## 📂 Files in this repo
- *version1_hardcoded.py* → Uses hardcoded values for a, b, c, t  
- *version2_keyboard_input.py* → Takes input from user via keyboard  
- *version3_file_input_single.py* → Reads one set of values from inputs_single.txt  
- *version4_file_input_multiple.py* → Reads multiple sets of values from inputs_multiple.txt  
- *inputs_single.txt* → Example single set of coefficients & time  
- *inputs_multiple.txt* → Example multiple sets of coefficients & time  

---

## ▶ How to Run

### Version 1 – Hardcoded
```bash
python version1_hardcoded.py
