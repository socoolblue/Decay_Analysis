# Decay_Analysis
A physics-informed framework using metaheuristic optimization, Runge–Kutta simulations, and physics-informed neural networks (PINN) to extract quantitative parameters from luminescence decay dynamics.

## Overview
This project explores a new paradigm for luminescence decay analysis by moving beyond traditional multi-exponential fitting. Using metaheuristic optimization, Runge–Kutta simulations, and physics-informed neural networks (PINN), we quantitatively extract radiative and non-radiative rate constants in a Eu²⁺-activated multi-site phosphor (La₂.₅₄₄Ca₁.₄₅₆Si₁₂O₄.₄₅₆N₁₆.₅₄₄:Eu²⁺).

## Motivation
Many LED phosphors exhibit multi-peak emissions due to activators at distinct crystallographic sites, yet conventional multi-exponential fitting fails to capture the underlying physics.
To address this limitation, we adopt nonlinear rate-equation modeling and overcome its computational challenges using metaheuristic optimization, Runge–Kutta methods, and physics-informed neural networks (PINN).
This enables quantitative and physically grounded analysis of donor–acceptor energy transfer in multi-site phosphors.

## Key Features
A hybrid metaheuristic and Runge–Kutta approach is proposed to extract multiple unknown parameters in luminescence decay dynamics.
Physics-informed neural networks (PINN) are employed to independently determine multiple rate constants with high fidelity.
A new physics-grounded paradigm is presented that integrates AI and physics for quantitative, non-empirical analysis of relaxation phenomena.
 
## How to use
Open either Decay_Analysis_GA_Runge-Kutta.ipynb or Decay_Analysis_PSO_Runge-Kutta.ipynb in Jupyter Notebook and execute the code. The optimization workflow will run, producing optimized decay curves along with the extracted eight-dimensional rate constants.
Open Decay_Analysis_PINN.ipynb, specify the checkpoint_path, and execute the code to initiate training. The PINN-based optimization will run, yielding both the optimized graphs and the final learned parameters.

## Reference
Lee, B.D., Seo, Y.H., Cho, M.Y., Hong, J.C., Park, W.B., & Sohn, K.-S.
Resolving energy transfer dynamics in Eu²⁺-activated multi-site phosphors via metaheuristic optimization and physics-informed neural networks
Sejong University & Sunchon National University

## Contact
Kee-Sun Sohn — kssohn@sejong.ac.kr

## License
This project is licensed under the MIT License.
