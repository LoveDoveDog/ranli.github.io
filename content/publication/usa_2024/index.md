---
title: "Uniformly Stable Algorithms for Adversarial Training and Beyond"
date: 2024-05-04
publishDate: 2024-05-04
authors: ["Jiancong Xiao", "Jiawei Zhang", "Zhi-Quan Luo", "Asuman Ozdaglar (Jiancong Xiao and Jiawei Zhang are the first authors)"]
publication_types: ["1"]
abstract: "In adversarial machine learning, neural networks suffer from a significant issue known as robust overfitting, where the robust test accuracy decreases over epochs (Rice et al., 2020). Recent research conducted by Xing et al.,2021; Xiao et al., 2022 has focused on studying the uniform stability of adversarial training. Their investigations revealed that SGD-based adversarial training fails to exhibit uniform stability, and the derived stability bounds align with the observed phenomenon of robust overfitting in experiments. This motivates us to develop uniformly stable algorithms specifically tailored for adversarial training. To this aim, we introduce Moreau envelope-$A$, a variant of the Moreau Envelope-type algorithm. We employ a Moreau envelope function to reframe the original problem as a min-min problem, separating the non-strong convexity and non-smoothness of the adversarial loss. Then, this approach alternates between solving the inner and outer minimization problems to achieve uniform stability without incurring additional computational overhead. In practical scenarios, we show the efficacy of ME-$A$ in mitigating the issue of robust overfitting. Beyond its application in adversarial training, this represents a fundamental result in uniform stability analysis, as ME-$A$ is the first algorithm to exhibit uniform stability for weakly-convex, non-smooth problems."
featured: false
publication: "*International Conference on Machine Learning (ICML 2024)*"
---
