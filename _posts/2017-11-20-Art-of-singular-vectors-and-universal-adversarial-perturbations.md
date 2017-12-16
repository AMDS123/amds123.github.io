---
layout: post
title: "Art of singular vectors and universal adversarial perturbations"
date: 2017-11-20 03:09:07
categories: arXiv_CV
tags: arXiv_CV Adversarial Attention Image_Classification Classification Relation
author: Valentin Khrulkov, Ivan Oseledets
mathjax: true
---

* content
{:toc}

##### Abstract
Vulnerability of Deep Neural Networks (DNNs) to adversarial attacks has been attracting a lot of attention in recent studies. It has been shown that for many state of the art DNNs performing image classification there exist universal adversarial perturbations --- image-agnostic perturbations mere addition of which to natural images with high probability leads to their misclassification. In this work we propose a new algorithm for constructing such universal perturbations. Our approach is based on computing the so-called $(p, q)$-singular vectors of the Jacobian matrices of hidden layers of a network. Resulting perturbations present interesting visual patterns, and by using only 64 images we were able to construct universal perturbations with more than 60 \% fooling rate on the dataset consisting of 50000 images. We also investigate a correlation between the maximal singular value of the Jacobian matrix and the fooling rate of the corresponding singular vector, and show that the constructed perturbations generalize across networks.

##### Abstract (translated by Google)
深度神经网络（DNNs）对敌对攻击的脆弱性在最近的研究中已经引起了很多关注。已经显示，对于许多现有技术的DNN执行图像分类，存在通用的对抗性扰动 - 图像不可知的扰动（仅在高自然图像中添加这种扰动）导致其错误分类。在这项工作中，我们提出了一个新的算法来构造这样的通用摄动。我们的方法是基于计算网络隐层的雅可比矩阵的所谓的$（p，q）$  - 奇异向量。由此产生的摄动呈现出令人感兴趣的视觉模式，通过仅使用64幅图像，我们就能够构建在由50000幅图像组成的数据集上具有超过60％的愚弄率的通用摄动。我们还研究了雅可比矩阵的最大奇异值与相应奇异向量的愚蠢率之间的相关性，表明构造的扰动在网络中泛化。

##### URL
[https://arxiv.org/abs/1709.03582](https://arxiv.org/abs/1709.03582)

##### PDF
[https://arxiv.org/pdf/1709.03582](https://arxiv.org/pdf/1709.03582)

