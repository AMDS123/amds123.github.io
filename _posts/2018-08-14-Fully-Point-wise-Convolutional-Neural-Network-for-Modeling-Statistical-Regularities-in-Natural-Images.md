---
layout: post
title: "Fully Point-wise Convolutional Neural Network for Modeling Statistical Regularities in Natural Images"
date: 2018-08-14 09:06:26
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Jing Zhang, Yang Cao, Yang Wang, Chenglin Wen, Chang Wen Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Modeling statistical regularity plays an essential role in ill-posed image processing problems. Recently, deep learning based methods have been presented to implicitly learn statistical representation of pixel distributions in natural images and leverage it as a constraint to facilitate subsequent tasks, such as color constancy and image dehazing. However, the existing CNN architecture is prone to variability and diversity of pixel intensity within and between local regions, which may result in inaccurate statistical representation. To address this problem, this paper presents a novel fully point-wise CNN architecture for modeling statistical regularities in natural images. Specifically, we propose to randomly shuffle the pixels in the origin images and leverage the shuffled image as input to make CNN more concerned with the statistical properties. Moreover, since the pixels in the shuffled image are independent identically distributed, we can replace all the large convolution kernels in CNN with point-wise ($1*1$) convolution kernels while maintaining the representation ability. Experimental results on two applications: color constancy and image dehazing, demonstrate the superiority of our proposed network over the existing architectures, i.e., using 1/10$\sim$1/100 network parameters and computational cost while achieving comparable performance.

##### Abstract (translated by Google)
建模统计规律在不适定图像处理问题中起着至关重要的作用。最近，已经提出了基于深度学习的方法来隐含地学习自然图像中的像素分布的统计表示，并将其用作约束以促进后续任务，例如颜色恒定性和图像去雾。然而，现有的CNN架构易于在局部区域内和之间的像素强度的可变性和多样性，这可能导致不准确的统计表示。为了解决这个问题，本文提出了一种新颖的完全逐点CNN架构，用于建模自然图像中的统计规律。具体来说，我们建议随机混洗原始图像中的像素，并利用混洗图像作为输入，使CNN更关注统计属性。此外，由于混洗图像中的像素是独立相同分布的，我们可以用点（$ 1 * 1 $）卷积核替换CNN中的所有大卷积核，同时保持表示能力。两个应用的实验结果：颜色恒定性和图像去雾，证明了我们提出的网络优于现有体系结构的优越性，即，使用1/10 $ \ sim $ 1/100网络参数和计算成本，同时实现相当的性能。

##### URL
[http://arxiv.org/abs/1801.06302](http://arxiv.org/abs/1801.06302)

##### PDF
[http://arxiv.org/pdf/1801.06302](http://arxiv.org/pdf/1801.06302)

