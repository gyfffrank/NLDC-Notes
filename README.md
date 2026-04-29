# Nonlinear Dynamics and Chaos — Comprehensive Lecture Notes

Complete, self-contained lecture notes for a course on **Nonlinear Dynamics and Chaos**, based on *Nonlinear Dynamics and Chaos* (3rd Edition) by Steven H. Strogatz.

## Contents

The notes cover the following topics in a self-contained manner, assuming a background in mathematical methods of physics (multivariable calculus, linear algebra, ODEs):

### Part I: One-Dimensional Flows
- **Flows on the Line** — Autonomous ODEs, fixed points, stability, linear stability analysis, potentials, existence & uniqueness, impossibility of oscillations
- **Bifurcations** — Saddle-node, transcritical, pitchfork (supercritical & subcritical), imperfect bifurcations, hysteresis, cusp catastrophe, applications (bead on rotating hoop, insect outbreak)
- **Flows on the Circle** — Oscillations, uniform & nonuniform oscillators, overdamped pendulum, Josephson junctions

### Part II: Two-Dimensional Flows
- **Linear Systems** — Eigenvalue classification, trace-determinant plane, nodes, saddles, spirals, centers
- **Phase Plane Analysis** — Nullclines, linearization (Jacobian), Hartman-Grobman theorem, competing species, conservative & reversible systems, index theory
- **Limit Cycles** — Ruling out closed orbits (gradient systems, Liapunov functions, Dulac's criterion), Poincaré-Bendixson theorem, Liénard systems, Van der Pol oscillator, relaxation oscillations
- **Bifurcations in 2D** — Hopf bifurcation (supercritical & subcritical), global bifurcations, Josephson junction (2D), coupled oscillators, quasiperiodicity, Poincaré maps

### Part III: Chaos
- **What Is Chaos?** — Formal definition, sensitive dependence, deterministic aperiodicity
- **Lorenz Equations** — Derivation, symmetry, dissipation, fixed points, bifurcation structure, strange attractor, Lorenz map, horizon time, AC-driven pendulum
- **One-Dimensional Maps** — Fixed points, cobwebs, logistic map, period-doubling cascade, Feigenbaum universality, periodic windows, Lyapunov exponents, renormalization
- **Fractals and Strange Attractors** — Box-counting dimension, self-similarity, Cantor set, Hénon map, Rössler system, stretching and folding

### Part IV: Collective Behavior
- **Kuramoto Model** — Synchronization, order parameter, mean-field reduction, self-consistency analysis, critical coupling, phase transition analogy

### Appendices
- Summary of key theorems
- Useful mathematical facts (Taylor expansion, Jacobian, Green's theorem, eigenvalues, polar coordinates)

## Building

Compile with:
```bash
pdflatex nldc_notes.tex
pdflatex nldc_notes.tex   # second pass for cross-references
```

Required LaTeX packages: `amsmath`, `amssymb`, `amsthm`, `mathtools`, `physics`, `hyperref`, `cleveref`, `tcolorbox`, `tikz`, `pgfplots`, `fancyhdr`, `titlesec`, `booktabs`, `cancel`, `bm`.

## License

These notes are for personal educational use.
