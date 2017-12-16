---
layout: post
title: "Pixel-wise object tracking"
date: 2017-11-20 15:30:41
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention Tracking Object_Tracking RNN
author: Yilin Song, Chenge Li, Yao Wang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel pixel-wise visual object tracking framework that can track any anonymous object in a noisy background. The framework consists of two submodels, a global attention model and a local segmentation model. The global model generates a region of interests (ROI) that the object may lie in the new frame based on the past object segmentation maps, while the local model segments the new image in the ROI. Each model uses a LSTM structure to model the temporal dynamics of the motion and appearance, respectively. To circumvent the dependency of the training data between the two models, we use an iterative update strategy. Once the models are trained, there is no need to refine them to track specific objects, making our method efficient compared to online learning approaches. We demonstrate our real time pixel-wise object tracking framework on a challenging VOT dataset

##### Abstract (translated by Google)
在本文中，我们提出了一个新的像素明智的视觉对象跟踪框架，可以跟踪嘈杂背景中的任何匿名对象。该框架由两个子模型组成，即全局注意模型和局部分割模型。全局模型根据过去的对象分割图生成一个感兴趣的区域（ROI），该对象可能位于新的框架中，而局部模型在ROI中分割新的图像。每个模型使用LSTM结构分别对运动和外观的时间动态进行建模。为了避免两个模型之间的训练数据的依赖性，我们使用迭代更新策略。一旦模型被训练完毕，就不需要对它们进行细化以跟踪特定的对象，与在线学习方法相比，我们的方法更有效率。我们展示了我们在具有挑战性的VOT数据集上的实时像素对象跟踪框架

##### URL
[https://arxiv.org/abs/1711.07377](https://arxiv.org/abs/1711.07377)

##### PDF
[https://arxiv.org/pdf/1711.07377](https://arxiv.org/pdf/1711.07377)

