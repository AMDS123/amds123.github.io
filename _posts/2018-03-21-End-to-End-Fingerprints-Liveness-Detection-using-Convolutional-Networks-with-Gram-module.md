---
layout: post
title: "End-to-End Fingerprints Liveness Detection using Convolutional Networks with Gram module"
date: 2018-03-21 10:11:27
categories: arXiv_CV
tags: arXiv_CV CNN Detection
author: Eunsoo Park, Xuenan Cui, Weonjin Kim, Hakil Kim
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes an end-to-end CNN(Convolutional Neural Networks) model that uses gram modules with parameters that are approximately 1.2MB in size to detect fake fingerprints. The proposed method assumes that texture is the most appropriate characteristic in fake fingerprint detection, and implements the gram module to extract textures from the CNN. The proposed CNN structure uses the fire module as the base model and uses the gram module for texture extraction. Tensors that passed the fire module will be joined with gram modules to create a gram matrix with the same spatial size. After 3 gram matrices extracted from different layers are combined with the channel axis, it becomes the basis for categorizing fake fingerprints. The experiment results had an average detection error of 2.61% from the LivDet 2011, 2013, 2015 data, proving that an end-to-end CNN structure with few parameters that is able to be used in fake fingerprint detection can be designed.

##### Abstract (translated by Google)
本文提出了一种端到端CNN（卷积神经网络）模型，该模型使用参数大小约为1.2MB的克模块来检测假指纹。所提出的方法假定纹理是假指纹检测中最适合的特征，并且实现了克模块以从CNN提取纹理。所提出的CNN结构使用消防模块作为基础模型，并使用克模块进行纹理提取。通过消防模块的张量将与克模块连接，以创建具有相同空间尺寸的克矩阵。将从不同层提取的3克矩阵与通道轴组合后，成为分类假指纹的基础。根据LivDet 2011,2013,2015的数据，实验结果的平均检测误差为2.61％，证明可以设计能够用于假指纹检测的参数很少的端到端CNN结构。

##### URL
[http://arxiv.org/abs/1803.07830](http://arxiv.org/abs/1803.07830)

##### PDF
[http://arxiv.org/pdf/1803.07830](http://arxiv.org/pdf/1803.07830)

