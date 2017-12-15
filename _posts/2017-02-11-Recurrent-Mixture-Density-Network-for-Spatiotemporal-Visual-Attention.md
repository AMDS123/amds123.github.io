---
layout: post
title: "Recurrent Mixture Density Network for Spatiotemporal Visual Attention"
date: 2017-02-11 10:05:06
categories: arXiv_CV
tags: arXiv_CV Salient Knowledge Attention CNN Classification Prediction Relation
author: Loris Bazzani, Hugo Larochelle, Lorenzo Torresani
mathjax: true
---

* content
{:toc}

##### Abstract
In many computer vision tasks, the relevant information to solve the problem at hand is mixed to irrelevant, distracting information. This has motivated researchers to design attentional models that can dynamically focus on parts of images or videos that are salient, e.g., by down-weighting irrelevant pixels. In this work, we propose a spatiotemporal attentional model that learns where to look in a video directly from human fixation data. We model visual attention with a mixture of Gaussians at each frame. This distribution is used to express the probability of saliency for each pixel. Time consistency in videos is modeled hierarchically by: 1) deep 3D convolutional features to represent spatial and short-term time relations and 2) a long short-term memory network on top that aggregates the clip-level representation of sequential clips and therefore expands the temporal domain from few frames to seconds. The parameters of the proposed model are optimized via maximum likelihood estimation using human fixations as training data, without knowledge of the action in each video. Our experiments on Hollywood2 show state-of-the-art performance on saliency prediction for video. We also show that our attentional model trained on Hollywood2 generalizes well to UCF101 and it can be leveraged to improve action classification accuracy on both datasets.

##### Abstract (translated by Google)
在许多计算机视觉任务中，解决手头问题的相关信息混杂在无关紧要，分散注意力的信息中。这促使研究人员设计注意力模型，可以动态地集中在显着的图像或视频部分，例如，通过减小不相关的像素。在这项工作中，我们提出了一个时空注意模型，可以从人类注视数据中直接了解视频的哪个部分。我们用高斯混合物在每一帧中对视觉注意力进行建模。这种分布被用来表示每个像素的显着性的概率。视频中的时间一致性的分层建模包括：1）表示空间和短期时间关系的深度3D卷积特征; 2）顶部的长期短期记忆网络，聚集了连续剪辑的剪辑级表示，因此扩展了时域从几帧到几秒。所提出的模型的参数通过使用人类注意力作为训练数据的最大似然估计来优化，而不知道每个视频中的动作。我们在Hollywood2上的实验展示了视频显着性预测方面的最新性能。我们还表明，我们在Hollywood2上训练的注意力模型可以很好地概括UCF101，并且可以用来改善两个数据集上的动作分类的准确性。

##### URL
[https://arxiv.org/abs/1603.08199](https://arxiv.org/abs/1603.08199)

##### PDF
[https://arxiv.org/pdf/1603.08199](https://arxiv.org/pdf/1603.08199)

