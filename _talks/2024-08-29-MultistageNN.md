---
title: "Multi-stage neural networks achieving machine precision"
collection: talks
category: invite
type: "Talk"
permalink: /talks/2024-8-29-MultistageNN
excerpt: 'Presenting the publication of Multi-stage Neural Networks and discussing its general applications.'
venue: "Monthly seminar at ANSYS"
date: 2024-08-29
location: "(Virtual)"
---

Deep learning techniques are increasingly applied to scientific problems, where the precision of networks is crucial. Despite being deemed as universal function approximators, neural networks, in practice, struggle to reduce the prediction errors below even with large network size and extended training iterations. To address this issue, we developed the multi-stage neural networks that divides the training process into different stages, with each stage using a new network that is optimized to fit the residue from the previous stage. In this talk, I will use heuristic example to illustrate the principle and feature of the method. More examples are used to demonstrate that the prediction error from the multi-stage training for both regression problems and physics-informed neural networks can nearly reach the machine-precision of double-floating point within a finite number of iterations. This advancement mitigate the longstanding accuracy limitation of neural network training, and enhance PINNs as robust tools for solving challenging differential equations in mathematics, such as blow-up problems.
