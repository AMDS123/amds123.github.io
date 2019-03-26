---
layout: post
title: "Joint Learning of Discriminative Low-dimensional Image Representations Based on Dictionary Learning and Two-layer Orthogonal Projections"
date: 2019-03-24 12:06:49
categories: arXiv_CV
tags: arXiv_CV Image_Caption Sparse CNN Image_Classification Optimization Classification Deep_Learning Gradient_Descent
author: Xian Wei, Hao Shen, Yuanxiang Li, Xuan Tang, Bo Jin, Lijun Zhao, Yi Lu Murphey
mathjax: true
---

* content
{:toc}

##### Abstract
This work investigates the problem of efficiently learning discriminative low-dimensional representations of multiclass large-scale image objects. We propose a generic deep learning approach by taking advantages of Convolutional Neural Networks (CNN), sparse dictionary learning, and orthogonal projections. CNN is not only powerful on feature extraction, but also robust to spatial variance and changes. Sparse dictionary learning is well known for disentangling nonlinear underlying discriminative factors in data. The orthogonal projection is a notable efficient tool to project multi-class data onto low dimensional discriminative subspace. The proposed procedure can be summarized as follows. At first, a CNN is employed to extract high-dimensional (HD) preliminary convolutional features. Secondly, to avoid the high computational cost of direct sparse coding on HD CNN features, we present to learn sparse representation (SR) in an orthogonal projected space over a taskdriven sparsifying dictionary. We then exploit the discriminative projection on SR. The whole learning process is treated as a joint optimization problem of trace quotient maximization, which involves the CNN parameters, the orthogonal projection on CNN features, the dictionary and the discriminative projection on sparse codes. The related cost function is well defined on product manifold of the Stiefel manifold, the Oblique manifold, and the Grassmann manifold. It is optimized via a geometrical stochastic gradient descent algorithm. Finally, the quality of dictionary and projections learned by the proposed approach is further investigated in terms of image classification. The experimental results show that the approach can achieve a strongly competitive performance with state-of-the-art image classification methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.09977](http://arxiv.org/abs/1903.09977)

##### PDF
[http://arxiv.org/pdf/1903.09977](http://arxiv.org/pdf/1903.09977)

