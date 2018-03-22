---
layout: post
title: "A Cascaded Convolutional Neural Network for Single Image Dehazing"
date: 2018-03-21 15:01:21
categories: arXiv_CV
tags: arXiv_CV CNN Quantitative
author: Chongyi Li, Jichang Guo, Fatih Porikli, Huazhu Fu, Yanwei Pang
mathjax: true
---

* content
{:toc}

##### Abstract
Images captured under outdoor scenes usually suffer from low contrast and limited visibility due to suspended atmospheric particles, which directly affects the quality of photos. Despite numerous image dehazing methods have been proposed, effective hazy image restoration remains a challenging problem. Existing learning-based methods usually predict the medium transmission by Convolutional Neural Networks (CNNs), but ignore the key global atmospheric light. Different from previous learning-based methods, we propose a flexible cascaded CNN for single hazy image restoration, which considers the medium transmission and global atmospheric light jointly by two task-driven subnetworks. Specifically, the medium transmission estimation subnetwork is inspired by the densely connected CNN while the global atmospheric light estimation subnetwork is a light-weight CNN. Besides, these two subnetworks are cascaded by sharing the common features. Finally, with the estimated model parameters, the haze-free image is obtained by the atmospheric scattering model inversion, which achieves more accurate and effective restoration performance. Qualitatively and quantitatively experimental results on the synthetic and real-world hazy images demonstrate that the proposed method effectively removes haze from such images, and outperforms several state-of-the-art dehazing methods.

##### Abstract (translated by Google)
在室外场景下拍摄的图像通常会因为悬浮的大气颗粒而导致低对比度和有限的可视性，直接影响照片的质量。尽管已经提出了许多图像除雾方法，但有效的模糊图像恢复仍然是一个具有挑战性的问题。现有的基于学习的方法通常可以预测卷积神经网络（CNN）的介质传输，但忽略关键的全球大气光。与以往的基于学习的方法不同，我们提出了一种灵活的单级朦胧图像恢复级联CNN，它考虑了由两个任务驱动的子网共同构成的中等传输和全局大气光。具体来说，中等传输估计子网络受密集连接的CNN启发，而全球大气光估计子网络为轻量级CNN。此外，这两个子网络通过共享共同特征而被级联。最后，利用估计的模型参数，通过大气散射模型反演获得无雾图像，实现更加准确和有效的恢复性能。对合成和真实世界模糊图像的定性和定量实验结果证明，所提出的方法有效地从这样的图像中去除雾霾，并且胜过几种最先进的去雾方法。

##### URL
[http://arxiv.org/abs/1803.07955](http://arxiv.org/abs/1803.07955)

##### PDF
[http://arxiv.org/pdf/1803.07955](http://arxiv.org/pdf/1803.07955)

