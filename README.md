# Hi, I'm Yefan Wu 

**Quantitative Researcher | Algorithm Engineer | Applied Mathematician**

I bridge the gap between **complex stochastic theories** and **high-performance numerical implementations**. I am passionate about extreme performance optimization, mathematical modeling, and pushing computational limits.

---

### Technical Highlights

* **Numerical Optimization & DEQs**: Developed a high-precision solver for Cascaded Monotone Equilibrium Networks (MonDEQs) from scratch using **PyTorch (Double Precision)**.
    * Achieved **$10^{-14}$ absolute precision**, proving numerical closure for coupled monotone inclusion problems.
    * Realized a **$1588\times$ computational speedup** by discovering an **Inexact Splitting regime ($k=1$)** that maintains global stability without local convergence.
    * Identified and suppressed the **"Dead Zone" latency** (750+ iterations) inherent in sequential solvers, enabling **Anytime Convergence** for real-time neuromorphic systems.
    * The core theoretical framework and convergence proofs are currently under review for a top-tier international conference in mathematical systems theory (**MTNS 2026**).

* **Continuous-Time Dynamics Modeling (Denison Research)**: Designed deterministic ODE frameworks to model population flux and state transitions (applied to Liver Fibrosis).
    * Solved high-dimensional linear ODE systems via **Matrix Exponentials**, eliminating numerical stepping errors and guaranteeing exact probability mass conservation for **irregularly sampled** longitudinal data.
    * Engineered a custom **Maximum Likelihood Estimation (MLE)** optimization pipeline; applied **AIC/BIC** criteria to rigorously penalize model complexity and prevent overfitting on **sparse transition matrices**.
    * Handled observational noise and diagnostic ambiguity by embedding **Mixture Likelihoods** (treating uncertain observations as latent probabilistic states).
    * Extended the analytical framework to non-autonomous systems $\mathbf{Q}(t)$ using **RK45 numerical integration** to simulate counterfactuals under dynamic, time-varying covariates.


* **Quantitative Portfolio Construction & Risk Management**: Architected an institutional-grade, Object-Oriented (OOP) toolkit for Strategic Asset Allocation (SAA) and model stress-testing.

  * Developed a robust **Mean-Variance Optimisation** engine utilising Sequential Least Squares Programming (**SLSQP**) to handle complex, real-world institutional mandates (e.g., asymmetric bounds, zero-weighting, and sector-level concentration caps).
  * Implemented an advanced **Model Fragility Testing** framework to evaluate optimizer behavior under stressed and economically unsound correlation regimes.
  * Engineered a numerical repair module using **Eigenvalue Decomposition** and **Clipping** to project non-Positive Semi-Definite (non-PSD) covariance matrices back onto the PSD cone, ensuring mathematical validity for corrupted market inputs.
  * Conducted dual-metric evaluations contrasting pure mathematical efficiency (Sharpe Ratio) against investor risk preferences (**Exponential Utility functions** under CARA assumptions).


* **Stochastic Dynamics & Complex Systems Modeling:** Modeled the impact of intrinsic noise on the reliability of bursting rhythms in high-dimensional biophysical networks (CA1 Pyramidal Cells).
  * Architected a 5D non-linear **Stochastic Differential Equation** (SDE) framework with multiplicative noise (square-root diffusion) to capture state-dependent volatility.
  * Engineered a decoupled Monte Carlo simulation engine, featuring a custom **Euler-Maruyama** solver and systematic deterministic ablation studies (factor knockouts), to identify dynamic bifurcations.
  * Quantified temporal reliability degradation by extracting event-driven signals (e.g., inter-burst intervals) across high-volume simulated paths and evaluated system resilience using statistical metrics (Coefficient of Variation).

---

### Tech Stack

* **Mathematics**: Stochastic Calculus, Measure Theory, Nonlinear Dynamics, Convex Optimization.
* **Programming**: Python (PyTorch, NumPy, SciPy, Pandas), R, MATLAB, MySQL.
* **Tools**: LaTeX, Git, Linux, XPPAUT.

---

###  Education background
* **Bachelor of Science in Mathematics, Financial Mathematics & Statistics** 
* **Focus:** Stochastic Processes, PDEs, Measure Theory, Numerical Analysis.
* **Honors:** Recipient of competitive research scholarships (Denison Research Scholar, VRI) and academic achievement awards.

---

###  Beyond the Math & Code
When I'm not debugging numerical solvers or proving convergence theorems, you can find me:
* **Extreme Solo Backpacking:** Exploring off-the-beaten-path destinations. Highlights include solo mountaineering in New Zealand's snow peaks and trekking the Australian Outback.
* **Audio & Signal Tinkering:** Playing electric guitar and obsessing over analog effect pedals & tone crafting. I'm a massive fan of Post-Rock, Shoegaze, and Space Rock (and a proud collector of rare first-pressing vinyls).
* **Strategy & Philosophy:** Playing Go (Weiqi), writing traditional Chinese poetry by hand, and exploring Taoist philosophy to find the signal in the noise.

*"Exploring the intersection of mathematical rigor and computational limits."*

**Reach me at**: [wuyefan718@gmail.com]
