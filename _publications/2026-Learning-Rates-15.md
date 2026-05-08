---
title: "Balancing Learning Rates Across Layers: Exact Two-Step Dynamics and Optimal Scaling in Linear Neural Networks"
collection: publications
category: conferences
permalink: /publication/2026-Learning-Rates-15
excerpt: "We study optimal learning-rate selection in two-layer and three-layer linear neural networks trained to learn a single-index target function. In particular, we derive the exact closed-form expressions for the gradients and test loss after one and two steps of gradient descent, enabling a precise characterization of early training dynamics. We characterize how learning rates should scale under the gradient approximation in the first two steps, and prove that performing updates with this approximation yields a tractable surrogate loss with a tight, small approximation error. This formulation enables the theoretical analysis of layer-wise learning rates and reveals a distinct early-training regime: test loss can be minimized by unequal learning rates at the initial step, while equal learning rates become optimal in subsequent steps. Our numerical experiments validate these theoretical predictions and demonstrate the importance of balancing layer-wise learning-rate during early training."
date: 2026-01-01
venue: 'ICML'
---
