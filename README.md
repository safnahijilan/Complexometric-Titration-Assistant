# Complexometric Titration Assistant

## An Interactive Analytical Chemistry Learning Tool

A web-based educational application developed to help students understand metal–ligand complex formation, conditional formation constants, and complexometric titration decisions.

This project was created as a first-year Chemical Engineering project to connect analytical chemistry concepts with scientific computing.

---

# Project Purpose

In analytical chemistry, the formation constant (K) describes the stability of a metal–ligand complex.

However, real laboratory conditions are affected by factors such as pH and ligand availability.

This tool helps students understand:

Chemical Information

↓

Equilibrium Calculation

↓

Conditional Formation Constant (K')

↓

Titration Feasibility

↓

Laboratory Interpretation


---

# Features

## 1. Conditional Formation Constant Calculator

Calculates:

log K' = log K − log αY(H)


Then:

K' = 10^(log K')


The tool explains:

- Formation constant
- Conditional formation constant
- EDTA availability
- Effect of pH


---

## 2. EDTA Titration Feasibility Analysis

Evaluates:

K' × [Metal]


Based on the analytical chemistry criterion:

If:

K'[Metal] > 10⁶


Quantitative titration is considered feasible.


---

## 3. pH Effect Visualisation

Shows how pH affects EDTA species distribution:

- H₄Y
- H₃Y⁻
- H₂Y²⁻
- HY³⁻
- Y⁴⁻


Explains why only Y⁴⁻ strongly binds metal ions.


---

## 4. Chemical Explanation System

The application explains:

- What each variable means
- Why calculations are performed
- How results affect laboratory decisions


---

# Scientific Concepts Used

- Complexometric titration
- Metal–ligand equilibrium
- Formation constants
- Conditional formation constants
- EDTA acid-base equilibria
- pH-dependent ligand availability


---

# Technologies Used

- HTML
- CSS
- JavaScript


No external libraries or frameworks were used.

---

# Model Assumptions

This educational model assumes:

✓ 1:1 metal–ligand complex formation

✓ Equilibrium conditions are reached

✓ Formation constant values are accurate

✓ Side reactions are neglected


Real experiments may be influenced by:

- competing ions
- temperature
- ionic strength
- precipitation reactions


---

# Live Demo

Netlify:

PASTE YOUR NETLIFY LINK HERE


GitHub Pages:

PASTE YOUR GITHUB PAGES LINK HERE


---

# Project Screenshots

(Add screenshots of the application interface here)

---

# Future Improvements

Possible future developments:

- Automatic database of metal–ligand formation constants
- Automatic αY(H) calculation from pKa values
- More ligand systems
- Integration with analytical chemistry databases


---

# Author

Safna Hijilan

Chemical Engineering Undergraduate

Interested in chemical engineering, analytical chemistry, and scientific computing.
