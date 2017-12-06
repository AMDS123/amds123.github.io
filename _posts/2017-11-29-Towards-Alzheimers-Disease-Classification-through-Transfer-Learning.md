---
layout: post
title: "Towards Alzheimer's Disease Classification through Transfer Learning"
date: 2017-11-29 21:40:36
categories: arXiv_CV
tags: arXiv_CV Deep_Learning Detection
author: Marcia Hon, Naimul Khan
mathjax: true
---

* content
{:toc}

##### Abstract
Detection of Alzheimer's Disease (AD) from neuroimaging data such as MRI through machine learning have been a subject of intense research in recent years. Recent success of deep learning in computer vision have progressed such research further. However, common limitations with such algorithms are reliance on a large number of training images, and requirement of careful optimization of the architecture of deep networks. In this paper, we attempt solving these issues with transfer learning, where state-of-the-art architectures such as VGG and Inception are initialized with pre-trained weights from large benchmark datasets consisting of natural images, and the fully-connected layer is re-trained with only a small number of MRI images. We employ image entropy to select the most informative slices for training. Through experimentation on the OASIS MRI dataset, we show that with training size almost 10 times smaller than the state-of-the-art, we reach comparable or even better performance than current deep-learning based methods.

##### Abstract (translated by Google)
近年来，通过机器学习从诸如MRI的神经影像数据检测阿尔茨海默氏病（AD）一直是深入研究的课题。计算机视觉深度学习的最近成功进一步推动了这种研究。然而，这种算法的常见局限性是依赖于大量的训练图像，并且需要仔细优化深度网络的体系结构。在本文中，我们尝试用传递学习来解决这些问题，其中VGG和Inception等最先进的体系结构通过预先训练的权重从包含自然图像的大型基准数据集进行初始化，而完全连接的层是只用少量的MRI图像重新训练。我们采用图像熵来选择最有信息的切片进行训练。通过对OASIS MRI数据集进行实验，我们发现在培训规模比现有技术水平小近10倍的情况下，我们达到了与当前深度学习方法相当甚至更好的性能。

##### URL
[https://arxiv.org/abs/1711.11117](https://arxiv.org/abs/1711.11117)

