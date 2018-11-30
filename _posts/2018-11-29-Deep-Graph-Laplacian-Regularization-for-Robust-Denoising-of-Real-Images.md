---
layout: post
title: "Deep Graph Laplacian Regularization for Robust Denoising of Real Images"
date: 2018-11-29 09:36:58
categories: arXiv_CV
tags: arXiv_CV Regularization Sparse CNN Deep_Learning
author: Jin Zeng, Jiahao Pang, Wenxiu Sun, Gene Cheung
mathjax: true
---

* content
{:toc}

##### Abstract
Recent developments in deep learning have revolutionized the paradigm of image restoration. However, its applications on real image denoising are still limited, due to its sensitivity to training data and the complex nature of real image noise. In this work, we combine the robustness merit of model-based approaches and the learning power of data-driven approaches for real image denoising. Specifically, by integrating graph Laplacian regularization as a trainable module into a deep learning framework, we are less susceptible to overfitting than pure CNN-based approaches, achieving higher robustness to small datasets and cross-domain denoising. First, a sparse neighborhood graph is built from the output of a convolutional neural network (CNN). Then the image is restored by solving an unconstrained quadratic programming problem, using a corresponding graph Laplacian regularizer as a prior term. The proposed restoration pipeline is fully differentiable and hence can be end-to-end trained. Experimental results demonstrate that our work is less prone to overfitting given small training data. It is also endowed with strong cross-domain generalization power, outperforming the state-of-the-art approaches by a remarkable margin.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1807.11637](http://arxiv.org/abs/1807.11637)

##### PDF
[http://arxiv.org/pdf/1807.11637](http://arxiv.org/pdf/1807.11637)

