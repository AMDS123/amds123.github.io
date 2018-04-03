---
layout: post
title: "Self-Supervised Relative Depth Learning for Urban Scene Understanding"
date: 2018-04-02 15:39:03
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Detection Relation
author: Huaizu Jiang, Erik Learned-Miller, Gustav Larsson, Michael Maire, Greg Shakhnarovich
mathjax: true
---

* content
{:toc}

##### Abstract
As an agent moves through the world, the apparent motion of scene elements is (usually) inversely proportional to their depth. It is natural for a learning agent to associate image patterns with the magnitude of their displacement over time: as the agent moves, faraway mountains don't move much; nearby trees move a lot. This natural relationship between the appearance of objects and their motion is a rich source of information about the world. In this work, we start by training a deep network, using fully automatic supervision, to predict relative scene depth from single images. The relative depth training images are automatically derived from simple videos of cars moving through a scene, using recent motion segmentation techniques, and no human-provided labels. This proxy task of predicting relative depth from a single image induces features in the network that result in large improvements in a set of downstream tasks including semantic segmentation, joint road segmentation and car detection, and monocular (absolute) depth estimation, over a network trained from scratch. The improvement on the semantic segmentation task is greater than those produced by any other automatically supervised methods. Moreover, for monocular depth estimation, our unsupervised pre-training method even outperforms supervised pre-training with ImageNet. In addition, we demonstrate benefits from learning to predict (unsupervised) relative depth in the specific videos associated with various downstream tasks. We adapt to the specific scenes in those tasks in an unsupervised manner to improve performance. In summary, for semantic segmentation, we present state-of-the-art results among methods that do not use supervised pre-training, and we even exceed the performance of supervised ImageNet pre-trained models for monocular depth estimation, achieving results that are comparable with state-of-the-art methods.

##### Abstract (translated by Google)
当代理在世界中移动时，场景元素的明显运动（通常）与其深度成反比。学习代理人很自然会将图像模式与他们在一段时间内的位移幅度联系起来：随着代理人的移动，遥远的山脉不会移动太多;附近的树木移动很多。物体外观与动作之间的这种自然关系是关于世界的丰富信息来源。在这项工作中，我们从训练一个深度网络开始，使用全自动监控来预测单个图像的相对场景深度。相对深度训练图像自动从简单的视频中通过场景移动，使用最近的运动分割技术，并且不提供人工提供的标签。这种预测来自单个图像的相对深度的代理任务引起网络中的特征，其导致在训练网络上的一组下游任务（包括语义分割，联合道路分割和汽车检测以及单目（绝对）深度估计）从头开始。语义分割任务的改进大于任何其他自动监督方法产生的改进。此外，对于单眼深度估计，我们的无监督预训练方法甚至超过了使用ImageNet进行有监督的预训练。此外，我们还演示了学习预测（无监督）与各种下游任务相关的特定视频中相对深度的好处。我们以无人监督的方式适应这些任务中的特定场景，以提高性能。总之，对于语义分割，我们在不使用监督预训练的方法中提供最先进的结果，甚至超过监督ImageNet预训练模型单眼深度估计的性能，实现的结果是与最先进的方法相媲美。

##### URL
[http://arxiv.org/abs/1712.04850](http://arxiv.org/abs/1712.04850)

##### PDF
[http://arxiv.org/pdf/1712.04850](http://arxiv.org/pdf/1712.04850)

