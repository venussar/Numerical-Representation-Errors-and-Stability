# Scientific Programming Exercises

This repository contains a collection of Python notebooks focused on scientific programming and numerical computation.  
The exercises explore mathematical series, numerical approximations, and binary operations.

##  Contents

1. **Approximation of π**  
   - Implementation of the Maclaurin series for `arctan(x)`.
   - Comparison of convergence speed for different formulas.

2. **Exponential Series**  
   - Evaluation of the series for `e^(-x)` and error analysis.

3. **Stirling’s Approximation**  
   - Calculation of factorial approximations and analysis of absolute and relative error.

4. **Quadratic Equation Solver**  
   - Implementation of numerical solutions for quadratic equations with improved accuracy.

5. **Binary to Integer Conversion (`myint`)**  
   - Custom implementation of a function that converts a 16-bit binary number into an integer,  
     compared against Python’s built-in `int()` function.

     ### Análisis de Convergencia de $\pi$ //APARTADO LAB_2

**Este ejercicio compara la eficiencia de dos métodos de aproximación de $\pi$:**

* **Gráfico de Convergencia:** Se genera una figura que compara los valores de $\pi$ obtenidos por dos métodos (la Serie de Maclaurin y probablemente la Serie de Leibniz del primer repositorio, u otro método implementado) como función del número de iteraciones.
* **Análisis:** Se determina qué método alcanza una **convergencia más rápida** y cuál requiere **menos términos** para lograr una precisión aceptable de $\pi$.

## ⚙️ Tecnologías Usadas

* **Python**
* **Google Colab** (Entorno de desarrollo)
* **NumPy** (Cálculo numérico)
* **Matplotlib** (Visualización de datos, crucial para el análisis de convergencia)

## 📈 Author
Developed by *[Carolina Andrea Rodas Castañeda]* as part of the **Metodos Computacionales** coursework.
