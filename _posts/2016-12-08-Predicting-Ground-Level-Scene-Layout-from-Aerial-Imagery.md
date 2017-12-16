---
layout: post
title: "Predicting Ground-Level Scene Layout from Aerial Imagery"
date: 2016-12-08 16:12:23
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation
author: Menghua Zhai, Zachary Bessinger, Scott Workman, Nathan Jacobs
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a novel strategy for learning to extract semantically meaningful features from aerial imagery. Instead of manually labeling the aerial imagery, we propose to predict (noisy) semantic features automatically extracted from co-located ground imagery. Our network architecture takes an aerial image as input, extracts features using a convolutional neural network, and then applies an adaptive transformation to map these features into the ground-level perspective. We use an end-to-end learning approach to minimize the difference between the semantic segmentation extracted directly from the ground image and the semantic segmentation predicted solely based on the aerial image. We show that a model learned using this strategy, with no additional training, is already capable of rough semantic labeling of aerial imagery. Furthermore, we demonstrate that by finetuning this model we can achieve more accurate semantic segmentation than two baseline initialization strategies. We use our network to address the task of estimating the geolocation and geoorientation of a ground image. Finally, we show how features extracted from an aerial image can be used to hallucinate a plausible ground-level panorama.

##### Abstract (translated by Google)
我们引入一种新的学习策略来从航空影像中提取语义上有意义的特征。我们建议预测（嘈杂的）自动提取的同位地面图像的语义特征，而不是手动标记航拍图像。我们的网络架构以空间图像作为输入，使用卷积神经网络提取特征，然后应用自适应变换将这些特征映射到地面视角。我们使用端到端的学习方法来最小化从地面图像直接提取的语义分割与仅基于空间图像预测的语义分割之间的差异。我们表明，使用这种策略学习的模型，没有额外的训练，已经能够对航空影像进行粗略的语义标记。此外，我们证明，通过微调这个模型，我们可以实现比两个基线初始化策略更准确的语义分割。我们使用我们的网络来处理估算地面图像的地理位置和地理定位的任务。最后，我们展示如何从空间图像中提取的特征可以用来幻想一个合理的地面全景。

##### URL
[https://arxiv.org/abs/1612.02709](https://arxiv.org/abs/1612.02709)

##### PDF
[https://arxiv.org/pdf/1612.02709](https://arxiv.org/pdf/1612.02709)

