---
layout: post
title: "Joint Denoising / Compression of Image Contours via Shape Prior and Context Tree"
date: 2017-04-30 04:27:07
categories: arXiv_CV
tags: arXiv_CV Object_Detection Action_Recognition Detection Recognition
author: Amin Zheng, Gene Cheung, Dinei Florencio
mathjax: true
---

* content
{:toc}

##### Abstract
With the advent of depth sensing technologies, the extraction of object contours in images---a common and important pre-processing step for later higher-level computer vision tasks like object detection and human action recognition---has become easier. However, acquisition noise in captured depth images means that detected contours suffer from unavoidable errors. In this paper, we propose to jointly denoise and compress detected contours in an image for bandwidth-constrained transmission to a client, who can then carry out aforementioned application-specific tasks using the decoded contours as input. We first prove theoretically that in general a joint denoising / compression approach can outperform a separate two-stage approach that first denoises then encodes contours lossily. Adopting a joint approach, we first propose a burst error model that models typical errors encountered in an observed string y of directional edges. We then formulate a rate-constrained maximum a posteriori (MAP) problem that trades off the posterior probability p(x'|y) of an estimated string x' given y with its code rate R(x'). We design a dynamic programming (DP) algorithm that solves the posed problem optimally, and propose a compact context representation called total suffix tree (TST) that can reduce complexity of the algorithm dramatically. Experimental results show that our joint denoising / compression scheme outperformed a competing separate scheme in rate-distortion performance noticeably.

##### Abstract (translated by Google)
随着深度传感技术的出现，图像中对象轮廓的提取 - 对于较高级别的计算机视觉任务（如对象检测和人体动作识别）来说，这是一个常见而重要的预处理步骤，变得更加容易。然而，捕获的深度图像中的采集噪声意味着检测到的轮廓遭受不可避免的错误。在本文中，我们建议联合去噪和压缩图像中检测到的轮廓，以便将带宽限制传输到客户端，客户端然后可以使用解码的轮廓作为输入执行上述应用特定的任务。我们首先在理论上证明，一般来说，联合去噪/压缩方法可以超越单独的两阶段方法，首先去噪然后损失轮廓编码。采用联合方法，我们首先提出了一个突发错误模型，该模型对在有向边的观测串y中遇到的典型错误进行建模。然后，我们制定一个速率约束的最大后验（MAP）问题，该问题的折算后的字符串x'的后验概率p（x'| y）与其编码率R（x'）相关。我们设计了一个动态规划（DP）算法，以最优的方式解决了这个问题，并提出了一个紧凑的上下文表示（total suffix tree，TST），可以显着降低算法的复杂度。实验结果表明，我们的联合去噪/压缩方案明显优于速率失真性能竞争分离方案。

##### URL
[https://arxiv.org/abs/1705.00268](https://arxiv.org/abs/1705.00268)

##### PDF
[https://arxiv.org/pdf/1705.00268](https://arxiv.org/pdf/1705.00268)

