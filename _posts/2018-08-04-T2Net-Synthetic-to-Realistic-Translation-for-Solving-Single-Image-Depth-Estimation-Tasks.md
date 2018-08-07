---
layout: post
title: "T2Net: Synthetic-to-Realistic Translation for Solving Single-Image Depth Estimation Tasks"
date: 2018-08-04 09:10:14
categories: arXiv_CV
tags: arXiv_CV Regularization GAN Prediction
author: Chuanxia Zheng, Tat-Jen Cham, Jianfei Cai
mathjax: true
---

* content
{:toc}

##### Abstract
Current methods for single-image depth estimation use training datasets with real image-depth pairs or stereo pairs, which are not easy to acquire. We propose a framework, trained on synthetic image-depth pairs and unpaired real images, that comprises an image translation network for enhancing realism of input images, followed by a depth prediction network. A key idea is having the first network act as a wide-spectrum input translator, taking in either synthetic or real images, and ideally producing minimally modified realistic images. This is done via a reconstruction loss when the training input is real, and GAN loss when synthetic, removing the need for heuristic self-regularization. The second network is trained on a task loss for synthetic image-depth pairs, with extra GAN loss to unify real and synthetic feature distributions. Importantly, the framework can be trained end-to-end, leading to good results, even surpassing early deep-learning methods that use real paired data.

##### Abstract (translated by Google)
用于单图像深度估计的当前方法使用具有实际图像深度对或立体对的训练数据集，其不容易获取。我们提出了一种在合成图像深度对和不成对的真实图像上训练的框架，其包括用于增强输入图像的真实性的图像转换网络，随后是深度预测网络。一个关键的想法是让第一个网络充当广谱输入转换器，接收合成或真实图像，并理想地产生最小修改的真实图像。这是通过在训练输入是真实时的重建损失和合成时的GAN损失来完成的，从而消除了对启发式自正规化的需要。第二个网络针对合成图像深度对的任务丢失进行训练，具有额外的GAN损失以统一实际和合成特征分布。重要的是，该框架可以端到端地进行培训，从而获得良好的结果，甚至超越使用真实配对数据的早期深度学习方法。

##### URL
[https://arxiv.org/abs/1808.01454](https://arxiv.org/abs/1808.01454)

##### PDF
[https://arxiv.org/pdf/1808.01454](https://arxiv.org/pdf/1808.01454)

