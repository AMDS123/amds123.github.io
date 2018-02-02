---
layout: post
title: "In Defense of Classical Image Processing: Fast Depth Completion on the CPU"
date: 2018-01-31 19:46:11
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Jason Ku, Ali Harakeh, Steven L. Waslander
mathjax: true
---

* content
{:toc}

##### Abstract
With the rise of data driven deep neural networks as a realization of universal function approximators, most research on computer vision problems has moved away from hand crafted classical image processing algorithms. This paper shows that with a well designed algorithm, we are capable of outperforming neural network based methods on the task of depth completion. The proposed algorithm is simple and fast, runs on the CPU, and relies only on basic image processing operations to perform depth completion of sparse LIDAR depth data. We evaluate our algorithm on the challenging KITTI depth completion benchmark, and at the time of submission, our method ranks first on the KITTI test server among all published methods. Furthermore, our algorithm is data independent, requiring no training data to perform the task at hand. The code written in Python will be made publicly available at https://github.com/kujason/ip_basic.

##### Abstract (translated by Google)
随着数据驱动的深度神经网络作为通用函数逼近器的实现的兴起，大多数关于计算机视觉问题的研究已经从手工制作的经典图像处理算法转移开来。本文表明，通过设计良好的算法，我们能够在深度完成任务方面超越基于神经网络的方法。该算法简单快速，运行在CPU上，仅依靠基本的图像处理操作来完成稀疏LIDAR深度数据的深度完成。我们对具有挑战性的KITTI深度完成基准评估我们的算法，在提交时，我们的方法在KITTI测试服务器中排名第一。此外，我们的算法是独立于数据的，不需要训练数据来执行手头的任务。用Python编写的代码将在https://github.com/kujason/ip_basic公开。

##### URL
[http://arxiv.org/abs/1802.00036](http://arxiv.org/abs/1802.00036)

##### PDF
[http://arxiv.org/pdf/1802.00036](http://arxiv.org/pdf/1802.00036)

