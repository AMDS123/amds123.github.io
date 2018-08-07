---
layout: post
title: "Stack-Captioning: Coarse-to-Fine Learning for Image Captioning"
date: 2018-03-14 09:31:38
categories: arXiv_CV
tags: arXiv_CV Image_Caption Reinforcement_Learning Caption Inference Prediction
author: Jiuxiang Gu, Jianfei Cai, Gang Wang, Tsuhan Chen
mathjax: true
---

* content
{:toc}

##### Abstract
The existing image captioning approaches typically train a one-stage sentence decoder, which is difficult to generate rich fine-grained descriptions. On the other hand, multi-stage image caption model is hard to train due to the vanishing gradient problem. In this paper, we propose a coarse-to-fine multi-stage prediction framework for image captioning, composed of multiple decoders each of which operates on the output of the previous stage, producing increasingly refined image descriptions. Our proposed learning approach addresses the difficulty of vanishing gradients during training by providing a learning objective function that enforces intermediate supervisions. Particularly, we optimize our model with a reinforcement learning approach which utilizes the output of each intermediate decoder's test-time inference algorithm as well as the output of its preceding decoder to normalize the rewards, which simultaneously solves the well-known exposure bias problem and the loss-evaluation mismatch problem. We extensively evaluate the proposed approach on MSCOCO and show that our approach can achieve the state-of-the-art performance.

##### Abstract (translated by Google)
现有的图像字幕方法通常训练一阶段句子解码器，这很难产生丰富的细粒度描述。另一方面，由于消失梯度问题，多阶段图像标题模型难以训练。在本文中，我们提出了一种用于图像字幕的粗到细多阶段预测框架，由多个解码器组成，每个解码器在前一阶段的输出上运行，产生越来越精细的图像描述。我们提出的学习方法通​​过提供强制执行中间监督的学习目标函数来解决训练期间消失梯度的困难。特别是，我们使用强化学习方法优化我们的模型，该方法利用每个中间解码器的测试时间推断算法的输出以及其前一个解码器的输出来规范化奖励，同时解决众所周知的暴露偏差问题和损失评估不匹配问题。我们广泛评估了MSCOCO的建议方法，并表明我们的方法可以实现最先进的性能。

##### URL
[https://arxiv.org/abs/1709.03376](https://arxiv.org/abs/1709.03376)

##### PDF
[https://arxiv.org/pdf/1709.03376](https://arxiv.org/pdf/1709.03376)

