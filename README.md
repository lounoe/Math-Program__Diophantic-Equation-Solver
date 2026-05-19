# 🧮 Diophantine Equation Solver (GUI)

This is a Python desktop application with a graphical user interface (Tkinter) that solves linear Diophantine equations of the form:

ax + by = c

It computes integer solutions when they exist and displays both the general solution and several example solutions.

---

## ✨ Features

- Graphical user interface using Tkinter
- Solves linear Diophantine equations
- Checks whether solutions exist using the GCD condition
- Computes a particular solution using the Extended Euclidean Algorithm
- Displays the general solution in parametric form
- Shows multiple integer solutions for different values of k

---

## 🧠 Mathematical concept

A linear Diophantine equation:

ax + by = c

has integer solutions if and only if:

gcd(a, b) divides c

If this condition is satisfied, the solution can be expressed as:

x = x0 + (b / d)k  
y = y0 - (a / d)k  

where:
- d = gcd(a, b)
- (x0, y0) is a particular solution
- k is any integer

---

## 🖥️ Interface

The application allows the user to:

- Enter values for a, b, and c
- Click a button to calculate solutions
- View results in a scrollable text area

---

## ▶️ How to run

Make sure you have Python 3 installed.

Run the program with:

```bash
python Ecdiof_1
```
---

## 🛠️ Technologies used

- Python 3
- Tkinter (GUI)
- math.gcd
- Extended Euclidean Algorithm

---

## 👨‍💻 Author

Lounoe

GitHub: https://github.com/Lounoe
