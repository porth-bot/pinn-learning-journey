# pinn-learning-journey
Daily log of learning Physics-Informed Neural Networks (PINNs) from scratch — theory, code, and experiments.
# 🧠 PINN Learning Journey

A structured, daily learning log documenting my journey into **Physics-Informed Neural Networks (PINNs)** — from foundational math and physics to building working solvers for differential equations.

## 📌 About

I'm dedicating **20–30 minutes on weekdays** and **~1 hour on weekends** to learning PINNs from the ground up. This repo tracks every day's progress — notes, code, experiments, and reflections.

**Goal:** Build a deep understanding of how neural networks can be constrained by physical laws (PDEs/ODEs) and apply PINNs to solve real-world physics problems.

## 🗂️ Structure
```
pinn-learning-journey/
├── logs/                  # Daily markdown logs
│   ├── week-01/
│   │   ├── day-01.md
│   │   ├── day-02.md
│   │   └── ...
│   └── week-02/
├── notebooks/             # Jupyter notebooks with experiments
├── src/                   # Reusable PINN code/modules
├── papers/                # Key papers and reading notes
├── resources.md           # Curated list of learning resources
└── README.md
```

## 📅 Daily Log Format

Each daily log follows this template:

- **Date & Day #**
- **Topic:** What I focused on
- **Time spent:** (actual)
- **Summary:** Key concepts learned
- **Code:** Links to any notebooks or scripts
- **Questions/Blockers:** Things I need to revisit
- **Next session:** What I plan to tackle next

## 🛣️ Roadmap

### Phase 1 — Foundations (Weeks 1–2)
- [ ] Review neural network basics (forward pass, backpropagation)
- [ ] Automatic differentiation deep dive (PyTorch autograd)
- [ ] ODEs and PDEs refresher (heat equation, wave equation, Burgers' equation)
- [ ] Loss function design: data loss vs. physics loss vs. boundary loss

### Phase 2 — Core PINNs (Weeks 3–5)
- [ ] Implement vanilla PINN for a simple ODE
- [ ] Solve 1D heat equation with PINN
- [ ] Solve Burgers' equation (classic PINN benchmark)
- [ ] Understand and implement boundary/initial condition enforcement
- [ ] Experiment with network architectures and activation functions

### Phase 3 — Advanced Topics (Weeks 6–8)
- [ ] Residual-based adaptive refinement (RAR)
- [ ] Transfer learning for PINNs
- [ ] Inverse problems with PINNs
- [ ] DeepXDE / NVIDIA Modulus frameworks
- [ ] Multi-scale and multi-physics problems

### Phase 4 — Projects (Weeks 9+)
- [ ] Apply PINNs to a domain-specific problem
- [ ] Reproduce results from a published paper
- [ ] Write a summary blog post / tutorial

## 📚 Key Resources

| Resource | Type |
|----------|------|
| [Raissi et al. 2019 — Original PINN Paper](https://doi.org/10.1016/j.jcp.2018.10.045) | Paper |
| [DeepXDE Documentation](https://deepxde.readthedocs.io/) | Library |
| [Steve Brunton's PINN Lectures (YouTube)](https://www.youtube.com/c/Eigensteve) | Video |
| [Ben Moseley's PINN Tutorial](https://benmoseley.blog/my-research/so-what-is-a-physics-informed-neural-network/) | Blog |
| [NVIDIA Modulus](https://developer.nvidia.com/modulus) | Framework |

## 🔧 Tech Stack

- **Python 3.10+**
- **PyTorch** (primary framework)
- **Jupyter Notebooks** (experiments)
- **Matplotlib** (visualization)
- **DeepXDE** (later phases)

## 🧪 Highlighted Experiments

> _This section will be updated as I complete notable experiments._

| Day | Experiment | Notebook |
|-----|-----------|----------|
| — | — | — |

## 📊 Progress Tracker

| Week | Days Completed | Topics Covered |
|------|---------------|----------------|
| 1 | 0/7 | — |

## 🤝 Contributing

This is a personal learning repo, but if you spot errors or have suggestions, feel free to open an issue!

## 📄 License

MIT
```

---

**Other files to include:**

**`.gitignore`:**
```
__pycache__/
*.pyc
.ipynb_checkpoints/
.venv/
*.egg-info/
dist/
build/
.DS_Store
