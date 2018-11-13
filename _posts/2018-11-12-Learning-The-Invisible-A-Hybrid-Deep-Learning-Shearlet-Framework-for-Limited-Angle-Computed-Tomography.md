---
layout: post
title: "Learning The Invisible: A Hybrid Deep Learning-Shearlet Framework for Limited Angle Computed Tomography"
date: 2018-11-12 08:36:42
categories: arXiv_CV
tags: arXiv_CV Regularization Sparse Deep_Learning
author: T. A. Bubba, G. Kutyniok, M. Lassas, M. M&#xe4;rz, W. Samek, S. Siltanen, V. Srinivasan
mathjax: true
---

* content
{:toc}

##### Abstract
The high complexity of various inverse problems poses a significant challenge to model-based reconstruction schemes, which in such situations often reach their limits. At the same time, we witness an exceptional success of data-based methodologies such as deep learning. However, in the context of inverse problems, deep neural networks mostly act as black box routines, used for instance for a somewhat unspecified removal of artifacts in classical image reconstructions. In this paper, we will focus on the severely ill-posed inverse problem of limited angle computed tomography, in which entire boundary sections are not captured in the measurements. We will develop a hybrid reconstruction framework that fuses model-based sparse regularization with data-driven deep learning. Our method is reliable in the sense that we only learn the part that can provably not be handled by model-based methods, while applying the theoretically controllable sparse regularization technique to the remaining parts. Such a decomposition into visible and invisible segments is achieved by means of the shearlet transform that allows to resolve wavefront sets in the phase space. Furthermore, this split enables us to assign the clear task of inferring unknown shearlet coefficients to the neural network and thereby offering an interpretation of its performance in the context of limited angle computed tomography. Our numerical experiments show that our algorithm significantly surpasses both pure model- and more data-based reconstruction methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.04602](http://arxiv.org/abs/1811.04602)

##### PDF
[http://arxiv.org/pdf/1811.04602](http://arxiv.org/pdf/1811.04602)

