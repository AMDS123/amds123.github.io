---
layout: post
title: "Action-Driven Object Detection with Top-Down Visual Attentions"
date: 2016-12-20 15:24:46
categories: arXiv_CV
tags: arXiv_CV Object_Detection Attention CNN Deep_Learning Detection
author: Donggeun Yoo, Sunggyun Park, Kyunghyun Paeng, Joon-Young Lee, In So Kweon
mathjax: true
---

* content
{:toc}

##### Abstract
A dominant paradigm for deep learning based object detection relies on a "bottom-up" approach using "passive" scoring of class agnostic proposals. These approaches are efficient but lack of holistic analysis of scene-level context. In this paper, we present an "action-driven" detection mechanism using our "top-down" visual attention model. We localize an object by taking sequential actions that the attention model provides. The attention model conditioned with an image region provides required actions to get closer toward a target object. An action at each time step is weak itself but an ensemble of the sequential actions makes a bounding-box accurately converge to a target object boundary. This attention model we call AttentionNet is composed of a convolutional neural network. During our whole detection procedure, we only utilize the actions from a single AttentionNet without any modules for object proposals nor post bounding-box regression. We evaluate our top-down detection mechanism over the PASCAL VOC series and ILSVRC CLS-LOC dataset, and achieve state-of-the-art performances compared to the major bottom-up detection methods. In particular, our detection mechanism shows a strong advantage in elaborate localization by outperforming Faster R-CNN with a margin of +7.1% over PASCAL VOC 2007 when we increase the IoU threshold for positive detection to 0.7.

##### Abstract (translated by Google)
基于深度学习的对象检测的主要范式依赖于使用类别不可知提议的“被动”评分的“自下而上”方法。这些方法是有效的，但缺乏对场景级环境的整体分析。在本文中，我们用“自上而下”的视觉注意模式提出一个“行动驱动”的检测机制。我们通过采取注意模型提供的连续动作来本地化对象。用图像区域调节的关注模型提供了需要的动作以更接近目标物体。在每个时间步的动作本身是弱的，但顺序动作的集合使得边界框准确地收敛到目标对象边界。这个我们称为AttentionNet的关注模型是由一个卷积神经网络组成的。在我们的整个检测过程中，我们只利用来自单个AttentionNet的动作，没有任何模块用于对象提议或者边界框回归。我们评估了PASCAL VOC系列和ILSVRC CLS-LOC数据集的自顶向下检测机制，并与主要的自下而上检测方法相比，实现了最先进的性能。特别是，我们的检测机制在精确定位方面显示了强大的优势，在我们将阳性检测的IoU阈值提高到0.7时，性能比PASCAL VOC 2007高出7.1％。

##### URL
[https://arxiv.org/abs/1612.06704](https://arxiv.org/abs/1612.06704)

##### PDF
[https://arxiv.org/pdf/1612.06704](https://arxiv.org/pdf/1612.06704)

