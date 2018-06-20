---
layout: post
title: "Learning to Update for Object Tracking"
date: 2018-06-19 07:31:37
categories: arXiv_CV
tags: arXiv_CV Tracking Object_Tracking RNN Gradient_Descent Relation
author: Bi Li, Wenxuan Xie, Wenjun Zeng, Wenyu Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Model update lies at the heart of object tracking.Generally, model update is formulated as an online learning problem where a target model is learned over the online training dataset. Our key innovation is to \emph{learn the online learning algorithm itself using large number of offline videos}, i.e., \emph{learning to update}. The learned updater takes as input the online training dataset and outputs an updated target model. As a first attempt, we design the learned updater based on recurrent neural networks (RNNs) and demonstrate its application in a template-based tracker and a correlation filter-based tracker. Our learned updater consistently improves the base trackers and runs faster than realtime on GPU while requiring small memory footprint during testing. Experiments on standard benchmarks demonstrate that our learned updater outperforms commonly used update baselines including the efficient exponential moving average (EMA)-based update and the well-designed stochastic gradient descent (SGD)-based update. Equipped with our learned updater, the template-based tracker achieves state-of-the-art performance among realtime trackers on GPU.

##### Abstract (translated by Google)
模型更新处于对象跟踪的核心。一般而言，模型更新被制定为在线学习问题，其中在在线训练数据集上学习目标模型。我们的关键创新是使用大量离线视频来学习在线学习算法本身，即\ emph {学习更新}。学习的更新器将在线训练数据集作为输入并输出更新的目标模型。作为第一次尝试，我们设计了基于递归神经网络（RNN）的学习更新器，并在基于模板的跟踪器和基于相关滤波器的跟踪器中演示了它的应用。我们学习的更新程序不断改进基础跟踪器，并且在GPU上运行得比实时更快，同时在测试期间需要较小的内存占用量。标准基准测试表明，我们学习的更新程序胜过了常用的更新基准，包括基于有效指数移动平均（EMA）的更新和精心设计的随机梯度下降（SGD）更新。配备了我们熟悉的更新程序，基于模板的跟踪程序可以在GPU上的实时跟踪程序中实现最先进的性能。

##### URL
[http://arxiv.org/abs/1806.07078](http://arxiv.org/abs/1806.07078)

##### PDF
[http://arxiv.org/pdf/1806.07078](http://arxiv.org/pdf/1806.07078)

