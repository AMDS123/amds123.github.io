---
layout: post
title: "MoDL: Model Based Deep Learning Architecture for Inverse Problems"
date: 2019-06-05 16:31:11
categories: arXiv_CV
tags: arXiv_CV Regularization CNN Optimization Deep_Learning
author: Hemant Kumar Aggarwal, Merry P. Mani, Mathews Jacob
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a model-based image reconstruction framework with a convolution neural network (CNN) based regularization prior. The proposed formulation provides a systematic approach for deriving deep architectures for inverse problems with the arbitrary structure. Since the forward model is explicitly accounted for, a smaller network with fewer parameters is sufficient to capture the image information compared to black-box deep learning approaches, thus reducing the demand for training data and training time. Since we rely on end-to-end training, the CNN weights are customized to the forward model, thus offering improved performance over approaches that rely on pre-trained denoisers. The main difference of the framework from existing end-to-end training strategies is the sharing of the network weights across iterations and channels. Our experiments show that the decoupling of the number of iterations from the network complexity offered by this approach provides benefits including lower demand for training data, reduced risk of overfitting, and implementations with significantly reduced memory footprint. We propose to enforce data-consistency by using numerical optimization blocks such as conjugate gradients algorithm within the network; this approach offers faster convergence per iteration, compared to methods that rely on proximal gradients steps to enforce data consistency. Our experiments show that the faster convergence translates to improved performance, especially when the available GPU memory restricts the number of iterations.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1712.02862](http://arxiv.org/abs/1712.02862)

##### PDF
[http://arxiv.org/pdf/1712.02862](http://arxiv.org/pdf/1712.02862)

