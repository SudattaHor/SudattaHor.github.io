---
title: "Escaping saddle points in variational quantum algorithms with perturbed gradient descent"
excerpt: 'Numerical experiments using Pennylane. Investigates the use of stochasticity to escape saddle points in
variational quantum algorithms (VQAs). Provides evidence that additional stochasticity can escape saddle
points, but may also lead to worse solutions.'
collection: projects
---

## Abstract

Variational quantum algorithms (VQAs), which
use classical algorithms to optimize parameter-
ized quantum circuits, are seen as the best hope
to achieve quantum advantage due to their wide
range of applications and compatibility with near-
term quantum computers. However, finding effi-
cient classical optimization strategies for VQAs
can be challenging. For example, the quantum ap-
proximate optimization algorithm (QAOA) has
loss landscapes that are generally non-convex,
and typical gradient descent optimization may
get stuck at bad local optima and saddle points. In
this work, we investigate the use of stochasticity
to escape saddle points. We provide evidence that
additional stochasticity can escape saddle points,
but may also lead to worse solutions.

[Download report here](http://sudattahor.github.io/files/report-pgd-for-vqas.pdf)

[View repository here](https://github.com/SudattaHor/PGD-for-VQAs)
