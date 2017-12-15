---
layout: post
title: "Unsupervised Learning from Continuous Video in a Scalable Predictive Recurrent Network"
date: 2016-09-30 17:41:41
categories: arXiv_CV
tags: arXiv_CV Knowledge Tracking Prediction Relation
author: Filip Piekniewski, Patryk Laurent, Csaba Petre, Micah Richert, Dimitry Fisher, Todd Hylton
mathjax: true
---

* content
{:toc}

##### Abstract
Understanding visual reality involves acquiring common-sense knowledge about countless regularities in the visual world, e.g., how illumination alters the appearance of objects in a scene, and how motion changes their apparent spatial relationship. These regularities are hard to label for training supervised machine learning algorithms; consequently, algorithms need to learn these regularities from the real world in an unsupervised way. We present a novel network meta-architecture that can learn world dynamics from raw, continuous video. The components of this network can be implemented using any algorithm that possesses three key capabilities: prediction of a signal over time, reduction of signal dimensionality (compression), and the ability to use supplementary contextual information to inform the prediction. The presented architecture is highly-parallelized and scalable, and is implemented using localized connectivity, processing, and learning. We demonstrate an implementation of this architecture where the components are built from multi-layer perceptrons. We apply the implementation to create a system capable of stable and robust visual tracking of objects as seen by a moving camera. Results show performance on par with or exceeding state-of-the-art tracking algorithms. The tracker can be trained in either fully supervised or unsupervised-then-briefly-supervised regimes. Success of the briefly-supervised regime suggests that the unsupervised portion of the model extracts useful information about visual reality. The results suggest a new class of AI algorithms that uniquely combine prediction and scalability in a way that makes them suitable for learning from and --- and eventually acting within --- the real world.

##### Abstract (translated by Google)
理解视觉现实包括获取关于视觉世界中无数规律的常识，例如，照明如何改变场景中物体的外观，以及运动如何改变其明显的空间关系。训练监督机器学习算法难以标记这些规则;因此，算法需要以无监督的方式从现实世界中学习这些规则。我们提出了一种新颖的网络元架构，可以从原始的，连续的视频中学习世界动态。可以使用具有三个关键能力的任何算法来实现该网络的组件：随着时间推移信号的预测，信号维度（压缩）的减少以及使用补充上下文信息来通知预测的能力。所提出的体系结构是高度并行和可扩展的，并且使用本地化的连接，处理和学习来实现。我们演示了这种架构的实现，其中组件是从多层感知器构建的。我们应用这个实现来创建一个系统，能够稳定和强大的移动摄像机所看到的物体的视觉跟踪。结果显示性能达到或超过了最先进的跟踪算法。跟踪者可以接受完全监督或无监督，然后短暂监督的制度。简单监督制度的成功表明，模型的无监督部分提取有关视觉现实的有用信息。结果提出了一种新的AI算法，它将预测和可扩展性独特地结合在一起，使得它们适合从现实世界中学习和最终在现实世界中运行。

##### URL
[https://arxiv.org/abs/1607.06854](https://arxiv.org/abs/1607.06854)

##### PDF
[https://arxiv.org/pdf/1607.06854](https://arxiv.org/pdf/1607.06854)

