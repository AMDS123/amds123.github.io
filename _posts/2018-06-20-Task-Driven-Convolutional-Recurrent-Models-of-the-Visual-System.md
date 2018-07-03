---
layout: post
title: "Task-Driven Convolutional Recurrent Models of the Visual System"
date: 2018-06-20 20:27:23
categories: arXiv_AI
tags: arXiv_AI CNN RNN Classification Quantitative Recognition
author: Aran Nayebi, Daniel Bear, Jonas Kubilius, Kohitij Kar, Surya Ganguli, David Sussillo, James J. DiCarlo, Daniel L. K. Yamins
mathjax: true
---

* content
{:toc}

##### Abstract
Feed-forward convolutional neural networks (CNNs) are currently state-of-the-art for object classification tasks such as ImageNet. Further, they are quantitatively accurate models of temporally-averaged responses of neurons in the primate brain's visual system. However, biological visual systems have two ubiquitous architectural features not shared with typical CNNs: local recurrence within cortical areas, and long-range feedback from downstream areas to upstream areas. Here we explored the role of recurrence in improving classification performance. We found that standard forms of recurrence (vanilla RNNs and LSTMs) do not perform well within deep CNNs on the ImageNet task. In contrast, custom cells that incorporated two structural features, bypassing and gating, were able to boost task accuracy substantially. We extended these design principles in an automated search over thousands of model architectures, which identified novel local recurrent cells and long-range feedback connections useful for object recognition. Moreover, these task-optimized ConvRNNs explained the dynamics of neural activity in the primate visual system better than feedforward networks, suggesting a role for the brain's recurrent connections in performing difficult visual behaviors.

##### Abstract (translated by Google)
前馈卷积神经网络（CNN）目前是对象分类任务（例如ImageNet）的最新技术。此外，它们是灵长类大脑视觉系统中神经元的时间平均响应的定量精确模型。然而，生物视觉系统具有两种无法与典型CNN共享的普遍存在的建筑特征：皮质区域内的局部复发，以及从下游区域到上游区域的远程反馈。在这里，我们探讨了复发在提高分类绩效中的作用。我们发现标准形式的复发（香草RNN和LSTM）在ImageNet任务的深度CNN中表现不佳。相比之下，包含两个结构特征（绕过和门控）的定制单元能够大大提高任务准确性。我们在数千种模型体系结构的自动搜索中扩展了这些设计原则，这些体系结构识别出新的局部复发细胞和用于物体识别的远程反馈连接。此外，这些任务优化的ConvRNNs比前馈网络更好地解释了灵长类动物视觉系统中神经活动的动态，表明大脑在执行困难的视觉行为中的反复连接的作用。

##### URL
[http://arxiv.org/abs/1807.00053](http://arxiv.org/abs/1807.00053)

##### PDF
[http://arxiv.org/pdf/1807.00053](http://arxiv.org/pdf/1807.00053)

