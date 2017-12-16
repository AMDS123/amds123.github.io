---
layout: post
title: "CNN-Based Projected Gradient Descent for Consistent Image Reconstruction"
date: 2017-09-06 12:55:56
categories: arXiv_CV
tags: arXiv_CV Sparse CNN Gradient_Descent
author: Harshit Gupta, Kyong Hwan Jin, Ha Q. Nguyen, Michael T. McCann, Michael Unser
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new method for image reconstruction which replaces the projector in a projected gradient descent (PGD) with a convolutional neural network (CNN). CNNs trained as high-dimensional (image-to-image) regressors have recently been used to efficiently solve inverse problems in imaging. However, these approaches lack a feedback mechanism to enforce that the reconstructed image is consistent with the measurements. This is crucial for inverse problems, and more so in biomedical imaging, where the reconstructions are used for diagnosis. In our scheme, the gradient descent enforces measurement consistency, while the CNN recursively projects the solution closer to the space of desired reconstruction images. We provide a formal framework to ensure that the classical PGD converges to a local minimizer of a non-convex constrained least-squares problem. When the projector is replaced with a CNN, we propose a relaxed PGD, which always converges. Finally, we propose a simple scheme to train a CNN to act like a projector. Our experiments on sparse view Computed Tomography (CT) reconstruction for both noiseless and noisy measurements show an improvement over the total-variation (TV) method and a recent CNN-based technique.

##### Abstract (translated by Google)
我们提出了一种新的图像重建方法，用卷积神经网络（CNN）在投影梯度下降（PGD）中代替投影机。 CNN被训练成高维（图像到图像）回归器近来被用来有效地解决成像中的逆问题。然而，这些方法缺乏反馈机制来强制重建图像与测量一致。这对逆向问题是至关重要的，在生物医学成像中重要的是用于诊断。在我们的方案中，梯度下降强制测量一致性，而CNN递归投影解决方案更接近期望的重建图像的空间。我们提供了一个正式的框架，以确保经典的PGD收敛到非凸约束最小二乘问题的局部最小值。当CNN更换投影机时，我们提出一个宽松的PGD，它总是收敛的。最后，我们提出一个简单的方案来训练一个CNN，就像投影仪一样。对于无噪声和噪声测量的稀疏视图计算机断层扫描（CT）重建的实验显示出总体变化（TV）方法和最近的基于CNN的技术的改进。

##### URL
[https://arxiv.org/abs/1709.01809](https://arxiv.org/abs/1709.01809)

##### PDF
[https://arxiv.org/pdf/1709.01809](https://arxiv.org/pdf/1709.01809)

