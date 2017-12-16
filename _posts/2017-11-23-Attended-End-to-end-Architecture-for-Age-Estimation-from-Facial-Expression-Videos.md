---
layout: post
title: "Attended End-to-end Architecture for Age Estimation from Facial Expression Videos"
date: 2017-11-23 13:43:49
categories: arXiv_CV
tags: arXiv_CV Salient Attention CNN Detection
author: Wenjie Pei, Hamdi Dibeklioğlu, Tadas Baltrušaitis, David M.J. Tax
mathjax: true
---

* content
{:toc}

##### Abstract
The main challenges of age estimation from facial expression videos lie not only in the modeling of the static facial appearance, but also in the capturing of the temporal facial dynamics. Traditional techniques to this problem focus on constructing handcrafted features to explore the discriminative information contained in facial appearance and dynamics separately. This relies on sophisticated feature-refinement and framework-design. In this paper, we present an end-to-end architecture for age estimation which is able to simultaneously learn both the appearance and dynamics of age from raw videos of facial expressions. Specifically, we employ convolutional neural networks to extract effective latent appearance representations and feed them into recurrent networks to model the temporal dynamics. More importantly, we propose to leverage attention models for salience detection in both the spatial domain for each single image and the temporal domain for the whole video as well. We design a specific spatially-indexed attention mechanism among the convolutional layers to extract the salient facial regions in each individual image, and a temporal attention layer to assign attention weights to each frame. This two-pronged approach not only improves the performance by allowing the model to focus on informative frames and facial areas, but it also offers an interpretable correspondence between the spatial facial regions as well as temporal frames, and the task of age estimation. We demonstrate the strong performance of our model in experiments on a large, gender-balanced database with 400 subjects with ages spanning from 8 to 76 years. Experiments reveal that our model exhibits significant superiority over the state-of-the-art methods given sufficient training data.

##### Abstract (translated by Google)
从面部表情视频的年龄估计的主要挑战不仅在于静态面部外观的建模，而且还在于捕捉时间面部动态。针对这一问题的传统技术着重于构建手工特征，分别探讨面部表情和动态中所包含的辨别信息。这依赖于复杂的功能细化和框架设计。在本文中，我们提出了一个年龄估计的端到端体系结构，它能够同时从面部表情的原始视频中学习年龄的外观和动态。具体来说，我们使用卷积神经网络来提取有效的潜在外观表示，并将它们馈送到循环网络中以对时间动态进行建模。更重要的是，我们建议在每个单个图像的空间域以及整个视频的时域内利用注意模型进行显着性检测。我们设计了卷积层之间的特定空间索引注意机制，以提取每个单独图像中的显着面部区域，以及时间关注层，以将关注权重分配给每个帧。这种双管齐下的方法不仅通过允许模型集中于信息帧和面部区域来提高性能，而且还提供了空间面部区域以及时间帧之间的可解释的对应关系以及年龄估计的任务。我们展示了我们的模型在一个大型的，性别平衡的数据库的实验中的强大性能，400个年龄从8岁到76岁的受试者。实验表明，我们的模型在充分的训练数据的情况下比现有技术的方法显示出显着的优越性。

##### URL
[https://arxiv.org/abs/1711.08690](https://arxiv.org/abs/1711.08690)

##### PDF
[https://arxiv.org/pdf/1711.08690](https://arxiv.org/pdf/1711.08690)

