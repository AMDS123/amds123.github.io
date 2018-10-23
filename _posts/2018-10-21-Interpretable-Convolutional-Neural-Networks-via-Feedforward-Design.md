---
layout: post
title: "Interpretable Convolutional Neural Networks via Feedforward Design"
date: 2018-10-21 06:20:48
categories: arXiv_CV
tags: arXiv_CV Adversarial CNN Classification Relation
author: C.-C. Jay Kuo, Min Zhang, Siyang Li, Jiali Duan, Yueru Chen
mathjax: true
---

* content
{:toc}

##### Abstract
The model parameters of convolutional neural networks (CNNs) are determined by backpropagation (BP). In this work, we propose an interpretable feedforward (FF) design without any BP as a reference. The FF design adopts a data-centric approach. It derives network parameters of the current layer based on data statistics from the output of the previous layer in a one-pass manner. To construct convolutional layers, we develop a new signal transform, called the Saab (Subspace Approximation with Adjusted Bias) transform. It is a variant of the principal component analysis (PCA) with an added bias vector to annihilate activation's nonlinearity. Multiple Saab transforms in cascade yield multiple convolutional layers. As to fully-connected (FC) layers, we construct them using a cascade of multi-stage linear least squared regressors (LSRs). The classification and robustness (against adversarial attacks) performances of BP- and FF-designed CNNs applied to the MNIST and the CIFAR-10 datasets are compared. Finally, we comment on the relationship between BP and FF designs.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.02786](http://arxiv.org/abs/1810.02786)

##### PDF
[http://arxiv.org/pdf/1810.02786](http://arxiv.org/pdf/1810.02786)

