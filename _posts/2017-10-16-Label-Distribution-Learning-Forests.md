---
layout: post
title: "Label Distribution Learning Forests"
date: 2017-10-16 21:05:45
categories: arXiv_CV
tags: arXiv_CV Represenation_Learning Prediction
author: Wei Shen, Kai Zhao, Yilu Guo, Alan Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
Label distribution learning (LDL) is a general learning framework, which assigns to an instance a distribution over a set of labels rather than a single label or multiple labels. Current LDL methods have either restricted assumptions on the expression form of the label distribution or limitations in representation learning, e.g., to learn deep features in an end-to-end manner. This paper presents label distribution learning forests (LDLFs) - a novel label distribution learning algorithm based on differentiable decision trees, which have several advantages: 1) Decision trees have the potential to model any general form of label distributions by a mixture of leaf node predictions. 2) The learning of differentiable decision trees can be combined with representation learning. We define a distribution-based loss function for a forest, enabling all the trees to be learned jointly, and show that an update function for leaf node predictions, which guarantees a strict decrease of the loss function, can be derived by variational bounding. The effectiveness of the proposed LDLFs is verified on several LDL tasks and a computer vision application, showing significant improvements to the state-of-the-art LDL methods.

##### Abstract (translated by Google)
标签分发学习（LDL）是一种通用的学习框架，它为一个实例分配一组标签而不是一个标签或多个标签。当前的LDL方法在标签分布的表达形式上有限制的假设或者在表示学习中的限制，例如以端对端的方式学习深度特征。本文提出了标签分布学习森林（LDLF） - 一种基于可微分决策树的标签分布学习算法，具有以下几个优点：1）决策树有可能通过混合叶节点预测来模拟任何一般形式的标签分布。 2）可微分决策树的学习可以结合表征学习。我们定义了一个基于分布的森林损失函数，使所有的树能够共同学习，并且通过变分边界可以导出叶节点预测的更新函数，从而保证了损失函数的严格下降。所提出的低密度脂蛋白的有效性在几项低密度脂蛋白任务和计算机视觉应用中得到验证，显示出对最先进的低密度脂蛋白方法的重大改进。

##### URL
[https://arxiv.org/abs/1702.06086](https://arxiv.org/abs/1702.06086)

##### PDF
[https://arxiv.org/pdf/1702.06086](https://arxiv.org/pdf/1702.06086)

