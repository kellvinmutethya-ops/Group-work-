BIT 2118: SCIENTIFIC COMPUTING

Individual Group Project – Python-Based Scientific Computing Solutions

Student Name: Kelvin Mutethya
Registration Number: BSCCS252609557
Course Code: BIT 2118
Course Title: Scientific Computing
Institution: Mount Kenya University

---

1. Project Overview

This repository contains my individual implementation of the BIT 2118 Scientific Computing project. The project focuses on applying Python programming and numerical methods to solve mathematical and scientific computing problems.

I developed and organized this repository to demonstrate my understanding of the major concepts covered in Scientific Computing, including numerical computation, matrix operations, linear algebra, root-finding techniques, interpolation, numerical integration, differential equations, optimization and Monte Carlo simulations.

In addition to implementing the mathematical methods, I explored how these techniques can be applied to practical situations in fields such as networking, engineering, computer graphics, finance, energy management and data analysis.

The project covers Tasks 2–20 and includes original Python implementations, parameter variation experiments, modified real-world applications, generated outputs and supporting documentation.

2. Project Objectives

The main objectives of this project were:

1. To develop practical programming skills using Python and scientific computing libraries.
2. To implement mathematical and numerical methods in solving computational problems.
3. To understand the mathematical principles and formulas behind each implemented method.
4. To investigate how changes in input parameters affect computational results.
5. To apply scientific computing techniques to different real-world scenarios.
6. To interpret numerical results using written explanations, calculations and graphical representations.
7. To develop an organized individual GitHub repository for documenting and presenting my work.

3. Repository Structure

I organized the project into separate directories to make the source code, experiments, modified applications and documentation easy to access.

BIT2118_Scientific_Computing/
│
├── README.md
├── requirements.txt
│
├── code/
│   ├── Task_02_numpy_arrays.py
│   ├── Task_03_vectorization.py
│   ├── Task_04_floating_point_errors.py
│   ├── Task_05_matrix_operations.py
│   ├── ...
│   └── Task_20_monte_carlo.py
│
├── changed_parameter/
│   ├── Task_02_numpy_arrays_changed.py
│   ├── ...
│
├── modified_case/
│   ├── Task_02_water_tank_modified.py
│   ├── ...
│
├── outputs/
│   └── Generated results, logs and graphical plots
│
└── docs/
    └── Individual task explanations and documentation

Description of the Directories

- code/ – Contains the main Python programs used to implement the scientific computing tasks.
- changed_parameter/ – Contains modified versions of selected programs where input parameters are varied to examine their effects on the results.
- modified_case/ – Contains extended applications of the numerical methods to different practical and real-world problems.
- outputs/ – Stores generated results, program outputs and graphical representations.
- docs/ – Contains detailed explanations of the mathematical concepts, formulas, implementation procedures and interpretations of the results.
- requirements.txt – Specifies the Python libraries required to execute the programs.

4. Implementation of Scientific Computing Tasks

The project covers the following mathematical and computational concepts:

Task| Concept| Implementation and Application
2| NumPy Arrays and Numerical Computation| Used NumPy arrays to process sensor readings and perform temperature conversions.
3| Mathematical Functions and Vectorization| Compared traditional loops with vectorized operations when processing network latency data.
4| Floating-Point Arithmetic and Errors| Examined absolute errors, relative errors and catastrophic cancellation in numerical calculations.
5| Matrix Algebra and Operations| Applied matrix operations to rotation and scaling transformations in computer graphics.
6| Systems of Linear Equations| Used linear algebra to solve resource allocation problems involving server loads.
7| Gaussian Elimination and LU Decomposition| Implemented matrix factorization techniques for solving systems of linear equations.
8| Iterative Methods| Applied Jacobi and Gauss-Seidel methods to estimate steady-state heat distribution.
9| Eigenvalues and Eigenvectors| Explored eigenvalue computations and their application in network analysis.
10| Bisection and Fixed-Point Methods| Applied root-finding techniques to determine thermal equilibrium conditions.
11| Newton-Raphson and Secant Methods| Used numerical root-finding methods in financial NPV and IRR calculations.
12| Nonlinear Systems| Solved nonlinear equations representing intersections between geometric curves.
13| Interpolation| Applied linear interpolation and cubic splines to estimate missing sensor readings.
14| Curve Fitting and Least Squares| Developed mathematical models for predicting server response times under increasing workloads.
15| Numerical Differentiation| Estimated velocity and acceleration from GPS-based position data.
16| Numerical Integration| Applied trapezoidal and Simpson's rules to estimate electrical energy consumption.
17| Ordinary Differential Equations (Euler Method)| Simulated temperature changes using Newton's law of cooling.
18| SciPy ODE Solvers| Modelled the charging behaviour of an RC electrical circuit.
19| Numerical Optimization| Investigated cost minimization in cloud server resource allocation.
20| Monte Carlo Methods| Used random simulations to analyse uncertainty and server overload risks.

5. Mathematical Methods and Formulas

Throughout the project, I identified the mathematical principles governing each computational task before implementing the corresponding Python solution.

Some of the major mathematical expressions used include:

a) Systems of Linear Equations

[
Ax=b
]

Used to determine unknown variables in systems of simultaneous linear equations.

b) Eigenvalue Problems

[
A\mathbf{v}=\lambda\mathbf{v}
]

Used to determine the eigenvalues and eigenvectors of a matrix.

c) Numerical Integration

[
I=\int_a^b f(x),dx
]

Used to approximate the area under a curve and estimate quantities such as energy consumption.

d) Least Squares Method

[
\min\sum_{i=1}^{n}(y_i-\hat{y}_i)^2
]

Used to determine the best-fitting mathematical model for a given dataset.

e) Absolute Error

[
E_a=|x_{\text{true}}-x_{\text{approx}}|
]

Used to measure the difference between the actual and approximate numerical values.

f) Relative Error

[
E_r=\frac{|x_{\text{true}}-x_{\text{approx}}|}
{|x_{\text{true}}|}
]

Used to measure numerical error relative to the true value.

These mathematical expressions provided the foundation for implementing and interpreting the numerical methods in Python.

6. Parameter Variation and Sensitivity Analysis

To investigate how input values influence computational results, I created a separate directory called "changed_parameter/".

In this section, I modified selected input parameters while keeping the underlying mathematical methods unchanged.

The experiments helped me examine:

- How changes in array sizes affect numerical computations.
- How different input values influence calculated outputs.
- How numerical accuracy changes with different computational parameters.
- How iterative methods respond to different initial values and stopping tolerances.
- How changes in simulation parameters affect the final results.

The purpose of these experiments was to understand the relationship between input parameters and computational outcomes rather than relying on a single set of values.

7. Modified Real-World Applications

To extend the practical application of the concepts, I created another directory called "modified_case/".

This section applies the original mathematical methods to different real-world situations.

Some of the applications explored include:

1. Water Tank Analysis: Applying numerical computation to water-level and volume-related calculations.
2. Network Performance: Using vectorization and numerical analysis to examine network latency.
3. Computer Graphics: Applying matrix transformations to represent rotation and scaling.
4. Electrical Engineering: Using differential equations to simulate RC circuit charging behaviour.
5. Energy Management: Estimating electrical energy consumption using numerical integration.
6. Cloud Computing: Applying optimization methods to resource allocation and operational cost reduction.
7. Risk Analysis: Using Monte Carlo simulations to investigate uncertainty in server performance.

Each modified application demonstrates how mathematical and computational techniques can be adapted to solve problems beyond their original examples.

8. Results, Visualization and Interpretation

I used numerical outputs and graphical representations to examine and interpret the results obtained from the Python programs.

Where applicable, Matplotlib was used to generate graphs illustrating:

- Numerical convergence in iterative methods.
- Relationships between variables.
- Curve-fitting results.
- Temperature changes over time.
- Electrical circuit behaviour.
- Simulation outcomes and probability distributions.

The generated outputs are stored in the "outputs/" directory.

The accompanying documentation in "docs/" explains the results and their mathematical significance.

9. Python Libraries and Technologies

The project uses the following Python libraries and technologies:

Library/Technology| Purpose
Python 3.8+| Main programming language.
NumPy| Numerical calculations, arrays, matrices and random number generation.
SciPy| Advanced numerical methods, optimization, interpolation and integration.
Matplotlib| Graph generation and visualization of computational results.
Timeit| Measuring and comparing program execution times.
Git and GitHub| Version control and project hosting.

10. Installation and Execution

The project can be executed on a computer with Python installed.

Requirements

- Python 3.8 or later.
- pip package manager.
- Git (for cloning the repository).

Installing Dependencies

The required Python libraries are listed in "requirements.txt".

They can be installed using:

pip install -r requirements.txt

Running a Main Task

For example, to execute Task 2:

python code/Task_02_numpy_arrays.py

Running a Modified Application

To execute the modified water tank application:

python modified_case/Task_02_water_tank_modified.py

The commands above assume the files are available under the stated names and directory structure.

11. Learning Outcomes

Through this project, I have developed a better understanding of how mathematical concepts can be translated into computational solutions using Python.

The project has strengthened my ability to:

- Work with numerical data using NumPy.
- Perform matrix and linear algebra operations.
- Implement and compare numerical methods.
- Solve linear and nonlinear mathematical problems.
- Analyse numerical errors and computational accuracy.
- Use SciPy for advanced scientific calculations.
- Generate and interpret scientific graphs.
- Apply mathematical models to practical problems.
- Organize and document programming projects using GitHub.

12. Conclusion

This project demonstrates my practical understanding of Scientific Computing through the implementation of different numerical methods and their applications using Python.

By working through Tasks 2–20, I explored how mathematical models, numerical algorithms and programming techniques can be combined to solve scientific and real-world problems.

The inclusion of parameter variation experiments and modified case studies further demonstrates the importance of analysing computational results under different conditions.

Overall, this repository represents my individual academic work, practical programming experience and continued development of scientific computing skills.

---

Author

Kelvin Mutethya
Registration Number: BSCCS252609557
Course: BIT 2118 – Scientific Computing
Institution: Mount Kenya University

Individual Project Repository – 2026
