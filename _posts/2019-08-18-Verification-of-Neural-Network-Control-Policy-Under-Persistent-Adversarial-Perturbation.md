---
layout: post
title: "Verification of Neural Network Control Policy Under Persistent Adversarial Perturbation"
date: 2019-08-18 00:23:21
categories: arXiv_AI
tags: arXiv_AI Adversarial Image_Classification Classification
author: Yuh-Shyang Wang, Tsui-Wei Weng, Luca Daniel
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks are known to be fragile to small adversarial perturbations. This issue becomes more critical when a neural network is interconnected with a physical system in a closed loop. In this paper, we show how to combine recent works on neural network certification tools (which are mainly used in static settings such as image classification) with robust control theory to certify a neural network policy in a control loop. Specifically, we give a sufficient condition and an algorithm to ensure that the closed loop state and control constraints are satisfied when the persistent adversarial perturbation is l-infinity norm bounded. Our method is based on finding a positively invariant set of the closed loop dynamical system, and thus we do not require the differentiability or the continuity of the neural network policy. Along with the verification result, we also develop an effective attack strategy for neural network control systems that outperforms exhaustive Monte-Carlo search significantly. We show that our certification algorithm works well on learned models and achieves 5 times better result than the traditional Lipschitz-based method to certify the robustness of a neural network policy on a cart pole control problem.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.06353](http://arxiv.org/abs/1908.06353)

##### PDF
[http://arxiv.org/pdf/1908.06353](http://arxiv.org/pdf/1908.06353)

