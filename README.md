# 🌌 Fractol

> A graphical fractal explorer written in **C** using the **MiniLibX** library.

Fractol is a 42 project that introduces **complex numbers**, **mathematical visualization**, and **interactive graphics programming**.  
The program generates and displays famous fractals such as the **Mandelbrot** and **Julia sets**, allowing the user to explore them with smooth zooming and navigation.

---

# ✨ Features

• Render multiple fractal sets  
• Infinite zoom capability  
• Real-time interaction  
• Color shifting  
• Smooth navigation using mouse and keyboard  

Supported fractals:

- **Mandelbrot**
- **Julia**
- **Burning Ship** *(optional depending on implementation)*

---

# 🧠 Fractals Explained

A fractal is a mathematical structure that displays **self-similarity at different scales**.

This means when you zoom in, the pattern keeps repeating infinitely.

Fractals are generated using **iterative mathematical formulas** applied to **complex numbers**.

Example formula used in the Mandelbrot set:
z(n + 1) = z(n)² + c


Where:

- `z` is a complex number
- `c` is a constant representing a point on the complex plane

If the value escapes to infinity, the point **does not belong to the set**.

---

# 🖼️ Fractals

## Mandelbrot Set


::contentReference[oaicite:0]{index=0}


The Mandelbrot set is the most famous fractal.  
Each pixel corresponds to a complex number and determines whether the sequence diverges.

---

## Julia Set


::contentReference[oaicite:1]{index=1}


The Julia set uses the same formula as Mandelbrot but with a **fixed constant**.

Different constants generate **completely different shapes**.

---

# 🎮 Controls

| Key / Action | Function |
|------|------|
| Mouse Wheel | Zoom in / Zoom out |
| Arrow Keys | Move around |
| `+` / `-` | Change iteration depth |
| `C` | Change color palette |
| `ESC` | Exit program |

---
