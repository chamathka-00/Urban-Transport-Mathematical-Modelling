# Urban Transport Mathematical Modelling

This is a project applying core mathematical techniques — calculus, integration, series, and transforms — to real-world urban transportation problems, with a focus on bus and taxi systems in a city context.

---

## Overview

This project explores how mathematics can model, analyse, and optimise urban transport systems. Each section tackles a distinct problem using a different mathematical tool, implemented in Python.

---

## Contents

### 1. Modelling Travel Time
Uses multivariable calculus to model how distance and traffic delay affect travel time for buses and taxis. Computes partial derivatives and gradients using `sympy` to compare how each transport mode responds to congestion vs. distance.

### 2. Cost Analysis Using Integration
Derives fare functions for buses and taxis by integrating marginal cost expressions. Plots fare vs. distance curves to compare affordability across trip lengths.

### 3. Predicting Peak Travel Times Using Series Convergence
Models passenger volume over a 24-hour period using a truncated trigonometric and power series. Analyses where the approximation is valid and where the model breaks down due to series divergence.

### 4. Travel Pattern Analysis Using Fourier Transform
Applies the Fast Fourier Transform (FFT) to synthetic bus and taxi boarding count data to identify dominant demand frequencies (morning and evening rush hours). Discusses implications for scheduling and fleet management.

### 5. Image Processing Using Fourier and Discrete Cosine Transforms
Processes a vehicle licence plate image using 2D FFT and DCT. Covers grayscale conversion, frequency domain analysis, edge detection, and basic plate localisation — connecting the results to real-time traffic management applications.

---

## Requirements

```
numpy
matplotlib
sympy
scipy
```

Install dependencies with:

```bash
pip install numpy matplotlib sympy scipy
```

---

## Usage

Open the notebook in Jupyter:

```bash
jupyter notebook Urban_Transport_Mathematical_Modelling.ipynb
```

> **Note:** Section 5 requires a `vehicle_plate.png` image file to be present in the same directory as the notebook.

---

## Key Techniques

| Section | Technique |
|---|---|
| Travel Time | Partial derivatives, gradient vectors |
| Cost Analysis | Definite integration |
| Peak Times | Series approximation, convergence analysis |
| Travel Patterns | Fast Fourier Transform (FFT) |
| Image Processing | 2D FFT, Discrete Cosine Transform (DCT), edge detection |

---

## License

This project is intended for educational purposes.
