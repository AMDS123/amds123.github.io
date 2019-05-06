---
layout: post
title: "Intriguing Properties of Adversarial Examples"
date: 2017-11-08 06:54:49
categories: arXiv_CV
tags: arXiv_CV Adversarial NAS Reinforcement_Learning Prediction
author: Ekin D. Cubuk, Barret Zoph, Samuel S. Schoenholz, Quoc V. Le
mathjax: true
---

* content
{:toc}

##### Abstract
It is becoming increasingly clear that many machine learning classifiers are vulnerable to adversarial examples. In attempting to explain the origin of adversarial examples, previous studies have typically focused on the fact that neural networks operate on high dimensional data, they overfit, or they are too linear. Here we argue that the origin of adversarial examples is primarily due to an inherent uncertainty that neural networks have about their predictions. We show that the functional form of this uncertainty is independent of architecture, dataset, and training protocol; and depends only on the statistics of the logit differences of the network, which do not change significantly during training. This leads to adversarial error having a universal scaling, as a power-law, with respect to the size of the adversarial perturbation. We show that this universality holds for a broad range of datasets (MNIST, CIFAR10, ImageNet, and random data), models (including state-of-the-art deep networks, linear models, adversarially trained networks, and networks trained on randomly shuffled labels), and attacks (FGSM, step l.l., PGD). Motivated by these results, we study the effects of reducing prediction entropy on adversarial robustness. Finally, we study the effect of network architectures on adversarial sensitivity. To do this, we use neural architecture search with reinforcement learning to find adversarially robust architectures on CIFAR10. Our resulting architecture is more robust to white \emph{and} black box attacks compared to previous attempts.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1711.02846](https://arxiv.org/abs/1711.02846)

##### PDF
[https://arxiv.org/pdf/1711.02846](https://arxiv.org/pdf/1711.02846)

