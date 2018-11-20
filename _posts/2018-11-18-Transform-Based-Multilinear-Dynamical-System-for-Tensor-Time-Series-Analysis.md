---
layout: post
title: "Transform-Based Multilinear Dynamical System for Tensor Time Series Analysis"
date: 2018-11-18 15:45:31
categories: arXiv_AI
tags: arXiv_AI Prediction Relation
author: Weijun Lu, Xiao-Yang Liu, Qingwei Wu, Yue Sun, Anwar Walid
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel multilinear dynamical system (MLDS) in a transform domain, named $\mathcal{L}$-MLDS, to model tensor time series. With transformations applied to a tensor data, the latent multidimensional correlations among the frontal slices are built, and thus resulting in the computational independence in the transform domain. This allows the exact separability of the multi-dimensional problem into multiple smaller LDS problems. To estimate the system parameters, we utilize the expectation-maximization (EM) algorithm to determine the parameters of each LDS. Further, $\mathcal{L}$-MLDSs significantly reduce the model parameters and allows parallel processing. Our general $\mathcal{L}$-MLDS model is implemented based on different transforms: discrete Fourier transform, discrete cosine transform and discrete wavelet transform. Due to the nonlinearity of these transformations, $\mathcal{L}$-MLDS is able to capture the nonlinear correlations within the data unlike the MLDS \cite{rogers2013multilinear} which assumes multi-way linear correlations. Using four real datasets, the proposed $\mathcal{L}$-MLDS is shown to achieve much higher prediction accuracy than the state-of-the-art MLDS and LDS with an equal number of parameters under different noise models. In particular, the relative errors are reduced by $50\% \sim 99\%$. Simultaneously, $\mathcal{L}$-MLDS achieves an exponential improvement in the model's training time than MLDS.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.07342](http://arxiv.org/abs/1811.07342)

##### PDF
[http://arxiv.org/pdf/1811.07342](http://arxiv.org/pdf/1811.07342)

