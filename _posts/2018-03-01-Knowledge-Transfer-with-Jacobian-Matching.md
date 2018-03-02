---
layout: post
title: "Knowledge Transfer with Jacobian Matching"
date: 2018-03-01 15:31:26
categories: arXiv_CV
tags: arXiv_CV Knowledge Transfer_Learning
author: Suraj Srinivas, Francois Fleuret
mathjax: true
---

* content
{:toc}

##### Abstract
Classical distillation methods transfer representations from a "teacher" neural network to a "student" network by matching their output activations. Recent methods also match the Jacobians, or the gradient of output activations with the input. However, this involves making some ad hoc decisions, in particular, the choice of the loss function. 
 In this paper, we first establish an equivalence between Jacobian matching and distillation with input noise, from which we derive appropriate loss functions for Jacobian matching. We then rely on this analysis to apply Jacobian matching to transfer learning by establishing equivalence of a recent transfer learning procedure to distillation. 
 We then show experimentally on standard image datasets that Jacobian-based penalties improve distillation, robustness to noisy inputs, and transfer learning.

##### Abstract (translated by Google)
经典的蒸馏方法通过匹配它们的输出激活将代表从“教师”神经网络转移到“学生”网络。最近的方法也匹配Jacobians，或输出激活的梯度与输入。但是，这需要做出一些特别的决定，特别是选择损失函数。
 在本文中，我们首先建立雅可比矩阵匹配和蒸馏与输入噪声之间的等价关系，从中我们得出雅可比矩阵匹配的适当损失函数。然后，我们依靠这种分析来应用雅可比匹配来通过建立最近的转移学习过程与蒸馏的等价性来转移学习。
 然后，我们通过实验展示标准图像数据集，基于雅可比矩阵的惩罚改善蒸馏，对噪声输入的鲁棒性以及转移学习。

##### URL
[http://arxiv.org/abs/1803.00443](http://arxiv.org/abs/1803.00443)

##### PDF
[http://arxiv.org/pdf/1803.00443](http://arxiv.org/pdf/1803.00443)

