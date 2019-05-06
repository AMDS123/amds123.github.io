---
layout: post
title: "Reduced order modeling of subsurface multiphase flow models using deep residual recurrent neural networks"
date: 2018-10-24 14:33:29
categories: arXiv_CV
tags: arXiv_CV Face RNN
author: J.Nagoor Kani, Ahmed H. Elsheikh
mathjax: true
---

* content
{:toc}

##### Abstract
We present a reduced order modeling (ROM) technique for subsurface multi-phase flow problems building on the recently introduced deep residual recurrent neural network (DR-RNN) [1]. DR-RNN is a physics aware recurrent neural network for modeling the evolution of dynamical systems. The DR-RNN architecture is inspired by iterative update techniques of line search methods where a fixed number of layers are stacked together to minimize the residual (or reduced residual) of the physical model under consideration. In this manuscript, we combine DR-RNN with proper orthogonal decomposition (POD) and discrete empirical interpolation method (DEIM) to reduce the computational complexity associated with high-fidelity numerical simulations. In the presented formulation, POD is used to construct an optimal set of reduced basis functions and DEIM is employed to evaluate the nonlinear terms independent of the full-order model size. We demonstrate the proposed reduced model on two uncertainty quantification test cases using Monte-Carlo simulation of subsurface flow with random permeability field. The obtained results demonstrate that DR-RNN combined with POD-DEIM provides an accurate and stable reduced model with a fixed computational budget that is much less than the computational cost of standard POD-Galerkin reduced model combined with DEIM for nonlinear dynamical systems.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.10422](https://arxiv.org/abs/1810.10422)

##### PDF
[https://arxiv.org/pdf/1810.10422](https://arxiv.org/pdf/1810.10422)

