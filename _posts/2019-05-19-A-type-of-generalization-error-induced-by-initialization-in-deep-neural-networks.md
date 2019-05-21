---
layout: post
title: "A type of generalization error induced by initialization in deep neural networks"
date: 2019-05-19 17:11:42
categories: arXiv_AI
tags: arXiv_AI Quantitative
author: Yaoyu Zhang, Zhi-Qin John Xu, Tao Luo, Zheng Ma
mathjax: true
---

* content
{:toc}

##### Abstract
How different initializations and loss functions affect the learning of a deep neural network (DNN), specifically its generalization error, is an important problem in practice. In this work, focusing on regression problems, we develop a kernel-norm minimization framework for the analysis of DNNs in the kernel regime in which the number of neurons in each hidden layer is sufficiently large (Jacot et al. 2018, Lee et al. 2019). We find that, in the kernel regime, for any loss in a general class of functions, e.g., any Lp loss for $1 &lt; p &lt; \infty$, the DNN finds the same global minima-the one that is nearest to the initial value in the parameter space, or equivalently, the one that is closest to the initial DNN output in the corresponding reproducing kernel Hilbert space. With this framework, we prove that a non-zero initial output increases the generalization error of DNN. We further propose an antisymmetrical initialization (ASI) trick that eliminates this type of error and accelerates the training. We also demonstrate experimentally that even for DNNs in the non-kernel regime, our theoretical analysis and the ASI trick remain effective. Overall, our work provides insight into how initialization and loss function quantitatively affect the generalization of DNNs, and also provides guidance for the training of DNNs.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.07777](http://arxiv.org/abs/1905.07777)

##### PDF
[http://arxiv.org/pdf/1905.07777](http://arxiv.org/pdf/1905.07777)

