---
title: "Euler operators for mis-specified physics-informed neural networks"
collection: publications
category: conferences
permalink: /publication/2024-07-17-Euler-operators-misspecified-PINNs
excerpt: 'Developing theoretical tools to detect the mis-specfication of inverse problems using PINNs and quantifying the generalized bounds for the mis-specified PINN problems.'
date: 2024-7-17
venue: 'ICML2024-AI4Science Workshop'
paperurl: 'https://openreview.net/forum?id=kkGR5fNq2J'
citation: 'C. Cowen-Breen, <b>Y. Wang</b>, C.-Y. Lai. (2024). &quot;Euler operators for mis-specified physics-informed neural networks.&quot; <i>ICML2024-AI4Science Workshop</i>.'
---

Integration between equations and data is ubiquitously useful in the physical sciences: for example, data assimilation plays an important role in generating seamless data for climate and geophysics applications. However, in many practical scenarios, we have only partial or imprecise knowledge of these equations, leading to mis-specified problems, i.e. problems for which there is no solution to the given equations when coupled with real-world data. Physics-informed neural networks (PINNs) have been increasingly used for data assimilation, yet their efficacy has primarily been demonstrated for well-specified problems where solutions for the given equation and data exist. Moreover, in applications involving real-world noisy data and complex PDEs, it is often difficult to know whether the given problem is mis-specified. We introduce a framework for deriving well-specified problems from mis-specified problems---based on the Euler operator (related to the Euler-Lagrange equation) and other tools from mathematical analysis---closing the gap between problems which may be mis-specified in practice and the already-proven theory for the well-specified case. Based on this framework, we propose a diagnostic tool for determining whether given PDE problems are mis-specified, and prove generalization bounds for mis-specified PINNs. Our contributions enhance PINN reliability in the presence of partial knowledge of governing equations or imperfect data.

