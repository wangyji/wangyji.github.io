---
title: "Multi-stage neural networks achieving machine precision"
collection: talks
category: invite
type: "Talk"
permalink: /talks/2024-04-14-MultistageNN
excerpt: 'Present the recent publication of Multistage Neural Networks and its application on discovering self-similar blow-up solutions to various fluid equations.'
venue: "FRG conference of PDEs of incompressible fluid flows, computer assisted proofs and neural networks"
date: 2024-04-14
location: "Minneapolis, MN"
---

Deep learning techniques are increasingly applied to scientific problems, where the precision of networks is crucial. Despite being deemed as universal function approximators, neural networks, in practice, struggle to reduce the prediction errors below even with large network size and extended training iterations. To address this issue, we developed the multi-stage neural networks that divides the training process into different stages, with each stage using a new network that is optimized to fit the residue from the previous stage. We demonstrate that the prediction error from the multi-stage training for both regression problems and physics-informed neural networks can nearly reach the machine-precision of double-floating point within a finite number of iterations. This advancement mitigate the longstanding accuracy limitation of neural network training, and enhance PINNs as robust tools for solving challenging differential equations.
