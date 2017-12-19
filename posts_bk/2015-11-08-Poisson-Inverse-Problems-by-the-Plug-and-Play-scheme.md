---
layout: post
title: "Poisson Inverse Problems by the Plug-and-Play scheme"
date: 2015-11-08 16:22:49
categories: arXiv_CV
tags: arXiv_CV
author: Arie Rond, Raja Giryes, Michael Elad
mathjax: true
---

* content
{:toc}

##### Abstract
The Anscombe transform offers an approximate conversion of a Poisson random variable into a Gaussian one. This transform is important and appealing, as it is easy to compute, and becomes handy in various inverse problems with Poisson noise contamination. Solution to such problems can be done by first applying the Anscombe transform, then applying a Gaussian-noise-oriented restoration algorithm of choice, and finally applying an inverse Anscombe transform. The appeal in this approach is due to the abundance of high-performance restoration algorithms designed for white additive Gaussian noise (we will refer to these hereafter as "Gaussian-solvers"). This process is known to work well for high SNR images, where the Anscombe transform provides a rather accurate approximation. When the noise level is high, the above path loses much of its effectiveness, and the common practice is to replace it with a direct treatment of the Poisson distribution. Naturally, with this we lose the ability to leverage on vastly available Gaussian-solvers. In this work we suggest a novel method for coupling Gaussian denoising algorithms to Poisson noisy inverse problems, which is based on a general approach termed "Plug-and-Play". Deploying the Plug-and-Play approach to such problems leads to an iterative scheme that repeats several key steps: 1) A convex programming task of simple form that can be easily treated; 2) A powerful Gaussian denoising algorithm of choice; and 3) A simple update step. Such a modular method, just like the Anscombe transform, enables other developers to plug their own Gaussian denoising algorithms to our scheme in an easy way. While the proposed method bares some similarity to the Anscombe operation, it is in fact based on a different mathematical basis, which holds true for all SNR ranges.

##### Abstract (translated by Google)
Anscombe变换提供了将泊松随机变量近似转换为高斯随机变量。这个变换很重要，很吸引人，因为它很容易计算，在泊松噪声污染的各种反问题中变得很方便。可以通过首先应用Anscombe变换，然后应用高斯噪声导向的选择性恢复算法，最后应用逆Anscombe变换来解决这些问题。这种方法的吸引力是由于大量高性能的恢复算法设计用于白加性高斯噪声（我们将在下文中称为“高斯求解器”）。对于高信噪比的图像，这个过程是已知的，Anscombe变换提供了一个相当准确的近似。当噪声水平较高时，上述路径丧失了很多有效性，通常的做法是用泊松分布的直接处理来代替它。很自然地，我们失去了利用大量可用的高斯求解器的能力。在这项工作中，我们提出了一种将高斯去噪算法与泊松噪声逆问题相结合的新方法，该方法基于一种被称为“即插即用”的通用方法。针对这些问题部署即插即用方法导致了一个重复的方案，重复几个关键步骤：1）简单形式的凸面编程任务，可以很容易地处理; 2）选择强大的高斯去噪算法; 3）简单的更新步骤。像Anscombe变换一样，这种模块化方法使其他开发人员能够轻松地将他们自己的高斯去噪算法插入到我们的方案中。虽然所提出的方法与Anscombe操作具有一些相似性，但实际上它基于不同的数学基础，这对于所有的SNR范围都是适用的。

##### URL
[https://arxiv.org/abs/1511.02500](https://arxiv.org/abs/1511.02500)

##### PDF
[https://arxiv.org/pdf/1511.02500](https://arxiv.org/pdf/1511.02500)

