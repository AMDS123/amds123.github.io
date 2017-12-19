---
layout: post
title: "Video Tracking Using Learned Hierarchical Features"
date: 2015-11-25 02:58:42
categories: arXiv_CV
tags: arXiv_CV Tracking Embedding CNN Object_Tracking
author: Li Wang, Ting Liu, Gang Wang, Kap Luk Chan, Qingxiong Yang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose an approach to learn hierarchical features for visual object tracking. First, we offline learn features robust to diverse motion patterns from auxiliary video sequences. The hierarchical features are learned via a two-layer convolutional neural network. Embedding the temporal slowness constraint in the stacked architecture makes the learned features robust to complicated motion transformations, which is important for visual object tracking. Then, given a target video sequence, we propose a domain adaptation module to online adapt the pre-learned features according to the specific target object. The adaptation is conducted in both layers of the deep feature learning module so as to include appearance information of the specific target object. As a result, the learned hierarchical features can be robust to both complicated motion transformations and appearance changes of target objects. We integrate our feature learning algorithm into three tracking methods. Experimental results demonstrate that significant improvement can be achieved using our learned hierarchical features, especially on video sequences with complicated motion transformations.

##### Abstract (translated by Google)
在本文中，我们提出了一种学习视觉对象跟踪的分层特征的方法。首先，我们离线学习辅助视频序列对各种运动模式的鲁棒性。通过双层卷积神经网络学习分层特征。将时滞性约束嵌入到堆叠体系结构中，使学习到的特征对复杂的运动转换具有鲁棒性，这对于视觉对象跟踪非常重要。然后，给定一个目标视频序列，我们提出了一个领域适应模块，以根据特定目标对象在线适应预先学习的特征。自适应在深度特征学习模块的两个层次中进行，以包括特定目标对象的外观信息。结果，所学习的分层特征对于复杂的运动变换和目标对象的外观变化都是稳健的。我们将我们的特征学习算法集成到三种跟踪方法中实验结果表明，使用我们学习的分层特征可以实现显着的改进，特别是对于具有复杂运动变换的视频序列。

##### URL
[https://arxiv.org/abs/1511.07940](https://arxiv.org/abs/1511.07940)

##### PDF
[https://arxiv.org/pdf/1511.07940](https://arxiv.org/pdf/1511.07940)

