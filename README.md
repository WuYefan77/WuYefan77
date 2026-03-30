# Hi, I'm Yefan Wu 

I am a **Quantitative Researcher & Algorithm Engineer** with a strong mathematical foundation and a passion for extreme performance optimization. My work bridges the gap between complex stochastic theories and high-performance numerical implementations.

---

### Technical Highlights

* **Numerical Optimization & DEQs**: Developed a high-precision solver for Monotone Equilibrium Networks (MonDEQs) from scratch.
    * Achieved **$10^{-14}$ absolute precision** (machine epsilon).
    * Realized a **1588x computational speedup** through an innovative Two-Loop Splitting algorithm and inexact splitting mechanisms.
    * The core theoretical framework has been submitted to a top-tier international conference in systems theory.

* **Continuous-Time Dynamics Modeling (Denison Research)**: Designed deterministic ODE frameworks to model population flux and state transitions (applied to Liver Fibrosis).
    * Solved high-dimensional linear ODE systems via **Matrix Exponentials**, eliminating numerical stepping errors and guaranteeing exact probability mass conservation for **irregularly sampled** longitudinal data.
    * Engineered a custom **Maximum Likelihood Estimation (MLE)** optimization pipeline; applied **AIC/BIC** criteria to rigorously penalize model complexity and prevent overfitting on **sparse transition matrices**.
    * Handled observational noise and diagnostic ambiguity by embedding **Mixture Likelihoods** (treating uncertain observations as latent probabilistic states).
    * Extended the analytical framework to non-autonomous systems $\mathbf{Q}(t)$ using **RK45 numerical integration** to simulate counterfactuals under dynamic, time-varying covariates.


* **Quantitative Finance & Pricing**: Built a modular engine for pricing complex financial derivatives.
    * Implemented **Monte Carlo simulations** and **Finite Difference Methods (PDE)** for Exotic Options pricing.
    * Applied **Variance Reduction** techniques to significantly enhance simulation efficiency.
    * Experienced in stochastic control and time-series modeling for dynamic portfolio optimization.

* **Stochastic Dynamics & Complex Systems Modeling**:
   * Architected a 5D non-linear Stochastic Differential Equation (SDE) framework with multiplicative noise (square-root diffusion) to model state-dependent volatility in biophysical networks.
   * Engineered a decoupled Monte Carlo engine featuring a custom Euler-Maruyama solver, memory-caching, and systematic deterministic ablation studies (factor knockouts) to identify dynamic bifurcations.
   * Quantified temporal reliability degradation by extracting event-driven signals (Coefficient of Variation of inter-burst intervals) across high-volume simulated paths to evaluate system resilience.

---

### Tech Stack

* **Mathematics**: Stochastic Calculus, Measure Theory, Nonlinear Dynamics, Convex Optimization.
* **Programming**: Python (PyTorch, NumPy, SciPy, Pandas), R, MATLAB, MySQL.
* **Tools**: LaTeX, Git, Linux, XPPAUT.

---

### Education

* **Bachelor of Science in Mathematics, Financial Mathematics & Statistics**
    * Focus: Stochastic Processes, PDEs, Measure Theory, and Numerical Analysis.
    * Honors: Recipient of multiple competitive research scholarships and academic achievement awards.

---

*"Exploring the intersection of mathematical rigor and computational limits."*

**Reach me at**: [wuyefan718@gmail.com]
