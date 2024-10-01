---
title: "Multi-stage Neural Networks: Function Approximator of Machine Precision"
collection: publications
category: papers
permalink: /publication/201-10-01-paper-title-number-3
excerpt: 'Introducing multi-stage training scheme for regression problems and PINNs to reach machine precision.'
date: 2024-05-01
venue: 'Journal of Computational Physics'
paperurl: 'https://doi.org/10.1016/j.jcp.2024.112865'
citation: '<b>Y. Wang</b>, C.-Y. Lai. (2024). &quot;Multi-stage Neural Networks: Function Approximator of Machine
Precision.&quot; <i>JJournal of Computational Physics</i>. <b>504</b>. 112865.'
---

Deep learning techniques are increasingly applied to scientific problems, where the precision of networks is crucial. Despite being deemed as universal function approximators, neural networks, in practice, struggle to reduce the prediction errors below 1e-5 even with large network size and extended training iterations. To address this issue, we developed the multi-stage neural networks that divides the training process into different stages, with each stage using a new network that is optimized to fit the residue from the previous stage. Across successive stages, the residue magnitudes decreases substantially and follows an inverse power-law relationship with the residue frequencies. The multi-stage neural networks effectively mitigate the spectral biases associated with regular neural networks, enabling them to capture the high frequency feature of target functions. We demonstrate that the prediction error from the multi-stage training for both regression problems and physics-informed neural networks can nearly reach the machine-precision of double-floating point within a finite number of iterations. Such levels of accuracy are rarely attainable using single neural networks alone.
