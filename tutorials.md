---
layout: default
title: Tutorials & Notes
nav_order: 2
---

# Tutorials

Here are the computational and theoretical problems we will cover in our TA sessions.

## Tutorial 1: The Gross-Pitaevskii Equation

The time-dependent Gross-Pitaevskii equation (GPE) for a Bose-Einstein Condensate is given by:

$$ i\hbar \frac{\partial \psi(\mathbf{r},t)}{\partial t} = \left[ -\frac{\hbar^2}{2m}\nabla^2 + V_{ext}(\mathbf{r}) + g|\psi(\mathbf{r},t)|^2 \right] \psi(\mathbf{r},t) $$

### Practice Questions
1.  Derive the stationary state GPE by substituting $\psi(\mathbf{r},t) = \phi(\mathbf{r})e^{-i\mu t/\hbar}$.
2.  Write a Python script using the Split-Step Fourier method to evolve this state.
