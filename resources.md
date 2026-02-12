# 📚 PINN Learning Resources

A curated collection of resources for learning Physics-Informed Neural Networks, organized by type and difficulty.

---

## 📄 Foundational Papers

| Paper | Authors | Year | Why It Matters |
|-------|---------|------|----------------|
| [Physics-Informed Neural Networks (Original)](https://doi.org/10.1016/j.jcp.2018.10.045) | Raissi, Perdikaris, Karniadakis | 2019 | **The** PINN paper — start here |
| [Hidden Fluid Mechanics](https://doi.org/10.1126/science.aaw4741) | Raissi, Yazdani, Karniadakis | 2020 | PINNs applied to fluid dynamics |
| [DeepXDE: A Deep Learning Library for Solving DEs](https://doi.org/10.1137/19M1274067) | Lu et al. | 2021 | Framework paper with great explanations |
| [When and Why PINNs Fail to Train](https://doi.org/10.1016/j.jcp.2021.110768) | Krishnapriyan et al. | 2021 | Critical for understanding PINN limitations |
| [On the Convergence of PINNs](https://arxiv.org/abs/2004.01806) | Shin, Darbon, Karniadakis | 2020 | Theoretical convergence guarantees |
| [Understanding and Mitigating Gradient Flow Pathologies](https://doi.org/10.1137/20M1318043) | Wang, Teng, Perdikaris | 2021 | Fixing training instabilities |
| [Adaptive Activation Functions for PINNs](https://doi.org/10.1016/j.jcp.2019.109136) | Jagtap, Kawaguchi, Karniadakis | 2020 | Improving convergence with adaptive activations |

## 🎥 Video Lectures & Tutorials

### Lecture Series
- **[Steve Brunton — Physics Informed Machine Learning](https://www.youtube.com/playlist?list=PLMrJAkhIeNNQ0BaKuBKY43k4xMo6NSbBa)** — Excellent overview of the field from a dynamical systems perspective
- **[Maziar Raissi — PINN Lectures](https://maziarraissi.github.io/PINNs/)** — From the creator of PINNs himself
- **[Machine Learning for Physics (Tübingen)](https://www.youtube.com/playlist?list=PLdWY2PB9BYe3HFhJO2H2OlHH0SnbRnLr8)** — Broader ML-for-science context

### Short Tutorials
- **[PINN in 10 Minutes (YouTube)](https://www.youtube.com/results?search_query=physics+informed+neural+networks+tutorial)** — Quick conceptual overviews
- **[DeepXDE Tutorials (YouTube)](https://www.youtube.com/results?search_query=deepxde+tutorial)** — Hands-on framework walkthroughs

## 📝 Blog Posts & Written Tutorials

- **[Ben Moseley — So What Is a Physics-Informed Neural Network?](https://benmoseley.blog/my-research/so-what-is-a-physics-informed-neural-network/)** — Best beginner-friendly explanation
- **[Towards Data Science — PINNs Guide](https://towardsdatascience.com/physics-informed-neural-networks-pinns-an-intuitive-guide-fff138069563)** — Step-by-step walkthrough with code
- **[Google DeepMind — Neural Network Differential Equation Solvers](https://deepmind.google/discover/blog/)** — Broader context of neural DE solvers
- **[JAX MD & Differentiable Physics](https://github.com/google/jax-md)** — Related differentiable physics paradigm

## 🛠️ Libraries & Frameworks

| Library | Language | Description |
|---------|----------|-------------|
| [DeepXDE](https://github.com/lululxvi/deepxde) | Python | Most popular PINN library, supports multiple backends |
| [NVIDIA Modulus](https://developer.nvidia.com/modulus) | Python | Industrial-grade PINN framework |
| [NeuralPDE.jl](https://github.com/SciML/NeuralPDE.jl) | Julia | Julia ecosystem for scientific ML |
| [PyDEns](https://github.com/analysiscenter/pydens) | Python | Lightweight PDE solver with neural nets |
| [SciANN](https://github.com/ehsanhaghighat/sciann) | Python (Keras) | Keras-based scientific computing with NNs |
| [PINA](https://github.com/mathLab/PINA) | Python (PyTorch) | Physics-Informed Neural networks for Advanced modeling |

## 📐 Math & Physics Prerequisites

### Differential Equations
- **[3Blue1Brown — Differential Equations](https://www.youtube.com/playlist?list=PLZHQObOWTQDNPOjrT6KVlfJuKtYTftqH6)** — Visual intuition
- **[MIT OCW 18.03 — Differential Equations](https://ocw.mit.edu/courses/18-03sc-differential-equations-fall-2011/)** — Full course
- **[Paul's Online Math Notes — DEs](https://tutorial.math.lamar.edu/Classes/DE/DE.aspx)** — Quick reference

### Automatic Differentiation
- **[PyTorch Autograd Tutorial](https://pytorch.org/tutorials/beginner/blitz/autograd_tutorial.html)** — Essential for implementing PINNs
- **[JAX Autodiff Cookbook](https://jax.readthedocs.io/en/latest/notebooks/autodiff_cookbook.html)** — Alternative framework perspective
- **[What is Automatic Differentiation?](https://arxiv.org/abs/1502.05767)** — Baydin et al. survey paper

### Neural Networks
- **[Andrej Karpathy — Neural Networks: Zero to Hero](https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ)** — Build NNs from scratch
- **[Deep Learning Book (Goodfellow et al.)](https://www.deeplearningbook.org/)** — Classic reference

## 🧪 Benchmark Problems

These are standard problems used to test PINN implementations:

| Problem | Equation | Difficulty |
|---------|----------|------------|
| Simple harmonic oscillator | ODE | ⭐ Beginner |
| 1D Heat Equation | PDE (parabolic) | ⭐ Beginner |
| 1D Advection Equation | PDE (hyperbolic) | ⭐⭐ Intermediate |
| Burgers' Equation | PDE (nonlinear) | ⭐⭐ Intermediate |
| Navier-Stokes (2D steady) | PDE system | ⭐⭐⭐ Advanced |
| Schrödinger Equation | PDE (complex) | ⭐⭐⭐ Advanced |
| Allen-Cahn Equation | PDE (reaction-diffusion) | ⭐⭐⭐ Advanced |

## 🗂️ GitHub Repos Worth Studying

- **[maziarraissi/PINNs](https://github.com/maziarraissi/PINNs)** — Original implementation by the author
- **[lululxvi/deepxde](https://github.com/lululxvi/deepxde)** — DeepXDE with tons of examples
- **[omniscientoctopus/Physics-Informed-Neural-Networks](https://github.com/omniscientoctopus/Physics-Informed-Neural-Networks)** — Beginner-friendly PyTorch implementations
- **[jayroxis/PINNs](https://github.com/jayroxis/PINNs)** — Clean PyTorch PINN examples

## 🎓 Courses

- **[Coursera — Physics-Informed Machine Learning (coming)](https://www.coursera.org/)** — Check for new offerings
- **[MIT 6.S898 — Deep Learning (with scientific applications)](https://ocw.mit.edu/)** — Relevant deep learning foundations
- **[Caltech — Learning from Data](https://home.work.caltech.edu/telecourse.html)** — ML theory foundations

---

> **Note:** This list is a living document. Resources are added as I discover them throughout the learning journey.
