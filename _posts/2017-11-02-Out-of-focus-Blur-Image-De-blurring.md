---
layout: post
title: "Out-of-focus Blur: Image De-blurring"
date: 2017-11-02 03:11:32
categories: arXiv_CV
tags: arXiv_CV Regularization
author: Yuzhen Lu
mathjax: true
---

* content
{:toc}

##### Abstract
Image de-blurring is important in many cases of imaging a real scene or object by a camera. This project focuses on de-blurring an image distorted by an out-of-focus blur through a simulation study. A pseudo-inverse filter is first explored but it fails because of severe noise amplification. Then Tikhonov regularization methods are employed, which produce greatly improved results compared to the pseudo-inverse filter. In Tikhonov regularization, the choice of the regularization parameter plays a critical rule in obtaining a high-quality image, and the regularized solutions possess a semi-convergence property. The best result, with the relative restoration error of 8.49%, is achieved when the prescribed discrepancy principle is used to decide an optimal value. Furthermore, an iterative method, Conjugated Gradient, is employed for image de-blurring, which is fast in computation and leads to an even better result with the relative restoration error of 8.22%. The number of iteration in CG acts as a regularization parameter, and the iterates have a semi-convergence property as well.

##### Abstract (translated by Google)
在许多使用相机对真实场景或物体进行成像的情况下，图像去模糊非常重要。这个项目的重点是通过模拟研究去模糊由于焦外模糊而失真的图像。首先研究伪逆滤波器，但由于噪声放大严重而失败。然后采用Tikhonov正则化方法，与伪逆滤波器相比，产生了大大改善的结果。在Tikhonov正则化中，正则化参数的选择对获得高质量图像起着决定性的作用，正则化解具有半收敛性质。当使用规定的差异原则来确定最佳值时，获得最好的结果，相对恢复误差为8.49％。此外，迭代方法，共轭梯度，用于图像去模糊，这是计算速度快，导致更好的结果，8.22％的相对恢复误差。 CG中的迭代次数作为正则化参数，迭代也具有半收敛性。

##### URL
[https://arxiv.org/abs/1710.00620](https://arxiv.org/abs/1710.00620)

##### PDF
[https://arxiv.org/pdf/1710.00620](https://arxiv.org/pdf/1710.00620)

