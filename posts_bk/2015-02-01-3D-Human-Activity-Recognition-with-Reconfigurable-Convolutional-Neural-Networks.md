---
layout: post
title: "3D Human Activity Recognition with Reconfigurable Convolutional Neural Networks"
date: 2015-02-01 13:57:58
categories: arXiv_CV
tags: arXiv_CV Attention CNN Optimization Inference Classification Recognition
author: Keze Wang, Xiaolong Wang, Liang Lin, Meng Wang, Wangmeng Zuo
mathjax: true
---

* content
{:toc}

##### Abstract
Human activity understanding with 3D/depth sensors has received increasing attention in multimedia processing and interactions. This work targets on developing a novel deep model for automatic activity recognition from RGB-D videos. We represent each human activity as an ensemble of cubic-like video segments, and learn to discover the temporal structures for a category of activities, i.e. how the activities to be decomposed in terms of classification. Our model can be regarded as a structured deep architecture, as it extends the convolutional neural networks (CNNs) by incorporating structure alternatives. Specifically, we build the network consisting of 3D convolutions and max-pooling operators over the video segments, and introduce the latent variables in each convolutional layer manipulating the activation of neurons. Our model thus advances existing approaches in two aspects: (i) it acts directly on the raw inputs (grayscale-depth data) to conduct recognition instead of relying on hand-crafted features, and (ii) the model structure can be dynamically adjusted accounting for the temporal variations of human activities, i.e. the network configuration is allowed to be partially activated during inference. For model training, we propose an EM-type optimization method that iteratively (i) discovers the latent structure by determining the decomposed actions for each training example, and (ii) learns the network parameters by using the back-propagation algorithm. Our approach is validated in challenging scenarios, and outperforms state-of-the-art methods. A large human activity database of RGB-D videos is presented in addition.

##### Abstract (translated by Google)
用3D /深度传感器理解人类活动在多媒体处理和交互中已经受到越来越多的关注。这项工作的目标是开发一个新的深度模型，从RGB-D视频自动活动识别。我们将每个人类活动表示为类立方体视频片段的集合，并学习发现一类活动的时间结构，即活动如何根据分类进行分解。我们的模型可以被看作是一个结构化的深层架构，因为它通过引入结构替代来扩展卷积神经网络（CNN）。具体而言，我们在视频片段上构建由三维卷积和最大池算子组成的网络，并在每个卷积层中引入潜在变量来操纵神经元的激活。因此，我们的模型在两个方面提出了现有的方法：（1）它直接对原始投入（灰度 - 深度数据）进行识别，而不是依靠手工特征;（2）模型结构可以动态调整会计对于人类活动的时间变化，即网络配置允许在推理期间被部分地激活。对于模型训练，我们提出了一种EM型优化方法，迭代式地（i）通过确定每个训练样本的分解动作来发现潜在结构，并且（ii）通过使用反向传播算法来学习网络参数。我们的方法在具有挑战性的情况下得到验证，并且胜过了最先进的方法。此外还介绍了一个大型的RGB-D视频人类活动数据库。

##### URL
[https://arxiv.org/abs/1501.06262](https://arxiv.org/abs/1501.06262)

##### PDF
[https://arxiv.org/pdf/1501.06262](https://arxiv.org/pdf/1501.06262)

