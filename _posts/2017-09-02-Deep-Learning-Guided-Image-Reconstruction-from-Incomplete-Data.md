---
layout: post
title: "Deep Learning-Guided Image Reconstruction from Incomplete Data"
date: 2017-09-02 14:15:24
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning Quantitative Gradient_Descent
author: Brendan Kelly, Thomas P. Matthews, Mark A. Anastasio
mathjax: true
---

* content
{:toc}

##### Abstract
An approach to incorporate deep learning within an iterative image reconstruction framework to reconstruct images from severely incomplete measurement data is presented. Specifically, we utilize a convolutional neural network (CNN) as a quasi-projection operator within a least squares minimization procedure. The CNN is trained to encode high level information about the class of images being imaged; this information is utilized to mitigate artifacts in intermediate images produced by use of an iterative method. The structure of the method was inspired by the proximal gradient descent method, where the proximal operator is replaced by a deep CNN and the gradient descent step is generalized by use of a linear reconstruction operator. It is demonstrated that this approach improves image quality for several cases of limited-view image reconstruction and that using a CNN in an iterative method increases performance compared to conventional image reconstruction approaches. We test our method on several limited-view image reconstruction problems. Qualitative and quantitative results demonstrate state-of-the-art performance.

##### Abstract (translated by Google)
介绍了一种将深度学习融入迭代图像重建框架以重建严重不完整测量数据的图像的方法。具体而言，我们利用卷积神经网络（CNN）作为最小二乘法最小化过程中的准投影算子。 CNN训练编码有关正在成像的图像类别的高级信息;该信息被用来减轻使用迭代方法产生的中间图像中的伪像。该方法的结构受到近端梯度下降法的启发，其中近端算子被深CNN代替，并且梯度下降步骤通过使用线性重构算子来推广。已经证明，这种方法在几种有限视图图像重建的情况下提高了图像质量，并且与常规图像重建方法相比，在迭代方法中使用CNN提高了性能。我们在几个有限视图图像重构问题上测试了我们的方法。定性和定量结果显示了最先进的性能。

##### URL
[https://arxiv.org/abs/1709.00584](https://arxiv.org/abs/1709.00584)

##### PDF
[https://arxiv.org/pdf/1709.00584](https://arxiv.org/pdf/1709.00584)

