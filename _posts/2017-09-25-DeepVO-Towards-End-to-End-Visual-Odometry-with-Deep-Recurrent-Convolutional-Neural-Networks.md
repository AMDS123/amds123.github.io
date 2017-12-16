---
layout: post
title: "DeepVO: Towards End-to-End Visual Odometry with Deep Recurrent Convolutional Neural Networks"
date: 2017-09-25 11:29:00
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN RNN Deep_Learning Relation
author: Sen Wang, Ronald Clark, Hongkai Wen, Niki Trigoni
mathjax: true
---

* content
{:toc}

##### Abstract
This paper studies monocular visual odometry (VO) problem. Most of existing VO algorithms are developed under a standard pipeline including feature extraction, feature matching, motion estimation, local optimisation, etc. Although some of them have demonstrated superior performance, they usually need to be carefully designed and specifically fine-tuned to work well in different environments. Some prior knowledge is also required to recover an absolute scale for monocular VO. This paper presents a novel end-to-end framework for monocular VO by using deep Recurrent Convolutional Neural Networks (RCNNs). Since it is trained and deployed in an end-to-end manner, it infers poses directly from a sequence of raw RGB images (videos) without adopting any module in the conventional VO pipeline. Based on the RCNNs, it not only automatically learns effective feature representation for the VO problem through Convolutional Neural Networks, but also implicitly models sequential dynamics and relations using deep Recurrent Neural Networks. Extensive experiments on the KITTI VO dataset show competitive performance to state-of-the-art methods, verifying that the end-to-end Deep Learning technique can be a viable complement to the traditional VO systems.

##### Abstract (translated by Google)
本文研究单眼视觉测量（VO）问题。现有的大多数VO算法都是在标准流水线下开发的，包括特征提取，特征匹配，运动估计，局部优化等等。尽管其中一些已经表现出优越的性能，但是通常需要精心设计和专门微调以使其工作良好在不同的环境中。一些先验知识也需要恢复单眼VO的绝对比例。本文采用深度递归卷积神经网络（RCNN），提出了一种新颖的单眼VO端到端框架。由于它是以端对端的方式进行训练和部署的，因此它不需要在传统的VO管道中采用任何模块，而是直接从一系列原始RGB图像（视频）推断出姿态。基于RCNN，它不仅可以通过卷积神经网络自动学习VO问题的有效特征表示，而且还可以隐式地使用深度递归神经网络建立顺序动力学和关系模型。在KITTI VO数据集上进行的大量实验显示了最先进的方法具有竞争力，验证了端到端深度学习技术可以成为传统VO系统的可行补充。

##### URL
[https://arxiv.org/abs/1709.08429](https://arxiv.org/abs/1709.08429)

##### PDF
[https://arxiv.org/pdf/1709.08429](https://arxiv.org/pdf/1709.08429)

