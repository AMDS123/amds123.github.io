---
layout: post
title: "Learned Primal-dual Reconstruction"
date: 2017-11-24 12:39:52
categories: arXiv_CV
tags: arXiv_CV GAN CNN Optimization Deep_Learning
author: Jonas Adler, Ozan Öktem
mathjax: true
---

* content
{:toc}

##### Abstract
We propose the Learned Primal-Dual algorithm for tomographic reconstruction. The algorithm accounts for a (possibly non-linear) forward operator in a deep neural network by unrolling a proximal primal-dual optimization method, but where the proximal operators have been replaced with convolutional neural networks. The algorithm is trained end-to-end, working directly from raw measured data and it does not depend on any initial reconstruction such as filtered back-projection (FBP). We compare performance of the proposed method on low dose computed tomography reconstruction against FBP, total variation (TV), and deep learning based post-processing of FBP. For the Shepp-Logan phantom we obtain >6 dB PSNR improvement against all compared methods. For human phantoms the corresponding improvement is 6.6 dB over TV and 2.2 dB over learned post-processing along with a substantial improvement in the structural similarity index. Finally, our algorithm involves only ten forward-back-projection computations, making the method feasible for time critical clinical applications.

##### Abstract (translated by Google)
我们提出了用于层析重建的Learned Primal-Dual算法。该算法通过展开近邻原始 - 对偶优化方法解释了在深度神经网络中的（可能是非线性的）前向运算符，但是近端运算符已经被卷积神经网络取代。该算法是端对端训练，直接从原始测量数据工作，它不依赖于任何初始重建，如滤波反投影（FBP）。我们比较了低剂量计算机断层扫描重建的方法与FBP，总变差（TV）和基于深度学习的FBP后处理的性能。对于Shepp-Logan体模，我们获得的所有比较方法的PSNR改善> 6 dB。对于人体模型，相应的改善是电视6.6分贝，学习后处理2.2分贝，同时结构相似性指数有显着改善。最后，我们的算法只涉及10个前向投影计算，使得该方法对于时间关键的临床应用是可行的。

##### URL
[https://arxiv.org/abs/1707.06474](https://arxiv.org/abs/1707.06474)

##### PDF
[https://arxiv.org/pdf/1707.06474](https://arxiv.org/pdf/1707.06474)

