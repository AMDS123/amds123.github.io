---
layout: post
title: "Towards Stable Symbol Grounding with Zero-Suppressed State AutoEncoder"
date: 2019-03-27 07:46:02
categories: arXiv_AI
tags: arXiv_AI Knowledge Optimization
author: Masataro Asai, Hiroshi Kajino
mathjax: true
---

* content
{:toc}

##### Abstract
While classical planning has been an active branch of AI, its applicability is limited to the tasks precisely modeled by humans. Fully automated high-level agents should be instead able to find a symbolic representation of an unknown environment without supervision, otherwise it exhibits the knowledge acquisition bottleneck. Meanwhile, Latplan (Asai and Fukunaga 2018) partially resolves the bottleneck with a neural network called State AutoEncoder (SAE). SAE obtains the propositional representation of the image-based puzzle domains with unsupervised learning, generates a state space and performs classical planning. In this paper, we identify the problematic, stochastic behavior of the SAE-produced propositions as a new sub-problem of symbol grounding problem, the symbol stability problem. Informally, symbols are stable when their referents (e.g. propositional values) do not change against small perturbation of the observation, and unstable symbols are harmful for symbolic reasoning. We analyze the problem in Latplan both formally and empirically, and propose "Zero-Suppressed SAE", an enhancement that stabilizes the propositions using the idea of closed-world assumption as a prior for NN optimization. We show that it finds the more stable propositions and the more compact representations, resulting in an improved success rate of Latplan. It is robust against various hyperparameters and eases the tuning effort, and also provides a weight pruning capability as a side effect.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.11277](http://arxiv.org/abs/1903.11277)

##### PDF
[http://arxiv.org/pdf/1903.11277](http://arxiv.org/pdf/1903.11277)

