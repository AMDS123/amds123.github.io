---
layout: post
title: "Learning Shape Priors for Single-View 3D Completion and Reconstruction"
date: 2018-09-13 17:23:13
categories: arXiv_AI
tags: arXiv_AI Adversarial Face CNN
author: Jiajun Wu, Chengkai Zhang, Xiuming Zhang, Zhoutong Zhang, William T. Freeman, Joshua B. Tenenbaum
mathjax: true
---

* content
{:toc}

##### Abstract
The problem of single-view 3D shape completion or reconstruction is challenging, because among the many possible shapes that explain an observation, most are implausible and do not correspond to natural objects. Recent research in the field has tackled this problem by exploiting the expressiveness of deep convolutional networks. In fact, there is another level of ambiguity that is often overlooked: among plausible shapes, there are still multiple shapes that fit the 2D image equally well; i.e., the ground truth shape is non-deterministic given a single-view input. Existing fully supervised approaches fail to address this issue, and often produce blurry mean shapes with smooth surfaces but no fine details. 
 In this paper, we propose ShapeHD, pushing the limit of single-view shape completion and reconstruction by integrating deep generative models with adversarially learned shape priors. The learned priors serve as a regularizer, penalizing the model only if its output is unrealistic, not if it deviates from the ground truth. Our design thus overcomes both levels of ambiguity aforementioned. Experiments demonstrate that ShapeHD outperforms state of the art by a large margin in both shape completion and shape reconstruction on multiple real datasets.

##### Abstract (translated by Google)
单视图3D形状完成或重建的问题具有挑战性，因为在解释观察的许多可能形状中，大多数是难以置信的并且不对应于自然对象。该领域的最新研究通过利用深度卷积网络的表现力来解决这个问题。实际上，还存在另一种常常被忽视的模糊性：在合理的形状中，仍有多种形状可以很好地适应2D图像;即，在给定单视图输入的情况下，地面实况形状是不确定的。现有的完全监督方法无法解决这个问题，并且通常会产生模糊的平均形状，表面光滑但没有精细的细节。
 在本文中，我们提出了ShapeHD，通过将深度生成模型与对抗性学习的形状先验相结合，推动单视图形状完成和重建的极限。学识渊博的先辈作为一个正规化者，只有在它的输出不切实际时才会对模型进行惩罚，而不是偏离基本事实。因此，我们的设计克服了前面提到的两种模糊性。实验证明，ShapeHD在多个真实数据集的形状完成和形状重建方面都大大超过了现有技术水平。

##### URL
[http://arxiv.org/abs/1809.05068](http://arxiv.org/abs/1809.05068)

##### PDF
[http://arxiv.org/pdf/1809.05068](http://arxiv.org/pdf/1809.05068)

