---
title: "Linearly Constrained Bilevel Optimization: A Smoothed Implicit Gradient Approach"
date: 2023-06-01
publishDate: 2023-06-12T09:48:22.162124Z
authors: ["Prashant Khanduri", "Ioannis Tsaknakis", "Yihua Zhang", "Jia Liu", "Sijia Liu", "Jiawei Zhang", "Mingyi Hong"]
publication_types: ["1"]
abstract: "This work develops analysis and algorithms for solving a class of bilevel optimization problems where the lower-level (LL) problems have linear constraints. Most of the existing approaches for constrained bilevel problems rely on value function-based approximate reformulations, which suffer from issues such as non-convex and non-differentiable constraints. In contrast, in this work, we develop an implicit gradient-based approach, which is easy to implement, and is suitable for machine learning applications. We first provide an in-depth understanding of the problem, by showing that the implicit objective for such problems is in general non-differentiable. However, if we add some small (linear) perturbation to the LL objective, the resulting implicit objective becomes differentiable almost surely. This key observation opens the door for developing (deterministic and stochastic) gradient-based algorithms similar to the state-of-the-art ones for unconstrained bi-level problems. We show that when the implicit function is assumed to be strongly-convex, convex, and weakly-convex, the resulting algorithms converge with guaranteed rate. Finally, we experimentally corroborate the theoretical findings and evaluate the performance of the proposed framework on numerical and adversarial learning problems."
featured: false
publication: "*International Conference on Machine Learning (ICML 2023)*"
---
