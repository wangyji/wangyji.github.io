---
title: "Differentiable neural-network solver for data assimilation of ice shelves in JAX"
collection: publications
category: manuscripts
permalink: /publication/2024-07-30-DIFFICE_jax
excerpt: 'Developing a differentiable neural-network solver for data assimilation of ICE shelves written in JAX.'
date: 2024-07-30
venue: 'Journal of Open Source Software'
citation: '<b>Y. Wang</b> and C.-Y. Lai. (2024). &quot;Differentiable neural-network solver for data assimilation of ice shelves in JAX.&quot; <i>under review</i>.'
---

The flow of Antarctic ice shelves is controlled by their viscosity structure, which cannot be directly measured at the continental scale. Misrepresenting viscosity in ice-dynamics simulations can lead to imprecise forecasts of ice sheet mass loss into the oceans and its consequential impact on global sea-level rise. With the continent-wide remote-sensing data available over the past decades, the viscosity of the ice shelves can be inferred by solving an inverse problem. We present `DIFFICE_jax`: a DIFFerentiable solver using physics-informed neural networks (PINNs) for data assimilation and inverse modeling of ICE shelves written in JAX. This Python package converts discretized remote-sensing data into meshless and differentiable functions, and infers the viscosity profile by directly solving the Shallow Shelf Approximation (SSA) equations for ice shelves. The inversion algorithm is implemented in JAX. The `DIFFICE_jax` package includes several advanced features beyond vanilla PINNs algorithms, including collocation points resampling, non-dimensionalization of data and equations, extended-PINNs (XPINNs), and viscosity exponential scaling function, which are essential for accurate inversion. The package is designed to be user-friendly and accessible for beginners. The GitHub repository also provides tutorial examples with Colab notebooks for users at different levels to reproduce the results and modify the code for their specific problems of interest.
