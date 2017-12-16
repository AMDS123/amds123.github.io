---
layout: post
title: "Recurrent 3D Attentional Networks for End-to-End Active Object Recognition in Cluttered Scenes"
date: 2016-10-14 01:25:09
categories: arXiv_CV
tags: arXiv_CV Attention Reinforcement_Learning RNN Recognition
author: Min Liu, Yifei Shi, Lintao Zheng, Kai Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Active vision is inherently attention-driven: The agent selects views of observation to best approach the vision task while improving its internal representation of the scene being observed. Inspired by the recent success of attention-based models in 2D vision tasks based on single RGB images, we propose to address the multi-view depth-based active object recognition using attention mechanism, through developing an end-to-end recurrent 3D attentional network. The architecture comprises of a recurrent neural network (RNN), storing and updating an internal representation, and two levels of spatial transformer units, guiding two-level attentions. Our model, trained with a 3D shape database, is able to iteratively attend to the best views targeting an object of interest for recognizing it, and focus on the object in each view for removing the background clutter. To realize 3D view selection, we derive a 3D spatial transformer network which is differentiable for training with back-propagation, achieving must faster convergence than the reinforcement learning employed by most existing attention-based models. Experiments show that our method outperforms state-of-the-art methods in cluttered scenes.

##### Abstract (translated by Google)
主动视觉本质上是注意力驱动的：主体选择观察视角以最好地接近视觉任务，同时改善其观察到的场景的内部表示。受基于关注模型在基于单一RGB图像的二维视觉任务中最近成功的启发，我们提出通过开发一个端到端循环的三维注意网络来解决基于多视点深度的主动对象识别的注意机制。该架构包括一个循环神经网络（RNN），存储和更新一个内部表示，以及两个层次的空间转换器单元，引导两个层次的关注。我们的模型通过三维形状数据库进行训练，能够反复关注以感兴趣的对象为目标的最佳视图，以便识别它，并将注意力集中在每个视图中的对象上以消除背景混乱。为了实现三维视图选择，我们导出了一个三维空间变换网络，该网络对于反向传播训练是可微分的，与大多数现有的基于关注的模型所采用的强化学习相比，实现了更快的收敛速度。实验表明，我们的方法在杂乱的场景中胜过了最先进的方法。

##### URL
[https://arxiv.org/abs/1610.04308](https://arxiv.org/abs/1610.04308)

##### PDF
[https://arxiv.org/pdf/1610.04308](https://arxiv.org/pdf/1610.04308)

