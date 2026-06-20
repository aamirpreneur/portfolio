---
layout: post
title: "High-Fidelity Surrogate Modeling: FEA with PINNs"
category: "Machine Learning"
excerpt: "Exploring how Physics-Informed Neural Networks can act as high-fidelity surrogates, replacing expensive Finite Element Analysis simulations."
---

Finite Element Analysis (FEA) has long been the gold standard for solid mechanics and structural simulations. However, evaluating complex geometries under dynamic loads remains computationally expensive.

In my recent research and project deliverables, I have explored the use of **Physics-Informed Neural Networks (PINNs)** as high-fidelity surrogate models. By embedding the governing partial differential equations directly into the loss function of the neural network, we can train models that respect physical boundaries and conservation laws with minimal data.

This approach significantly accelerates the simulation of elastoplasticity and contact stresses without sacrificing accuracy, proving to be a game-changer for iterative engineering design.
