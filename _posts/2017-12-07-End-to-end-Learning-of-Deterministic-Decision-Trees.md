---
layout: post
title: "End-to-end Learning of Deterministic Decision Trees"
date: 2017-12-07 17:40:25
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Thomas Hehn, Fred A. Hamprecht
mathjax: true
---

* content
{:toc}

##### Abstract
Conventional decision trees have a number of favorable properties, including interpretability, a small computational footprint and the ability to learn from little training data. However, they lack a key quality that has helped fuel the deep learning revolution: that of being end-to-end trainable, and to learn from scratch those features that best allow to solve a given supervised learning problem. Recent work (Kontschieder 2015) has addressed this deficit, but at the cost of losing a main attractive trait of decision trees: the fact that each sample is routed along a small subset of tree nodes only. We here propose a model and Expectation-Maximization training scheme for decision trees that are fully probabilistic at train time, but after a deterministic annealing process become deterministic at test time. We also analyze the learned oblique split parameters on image datasets and show that Neural Networks can be trained at each split node. In summary, we present the first end-to-end learning scheme for deterministic decision trees and present results on par with or superior to published standard oblique decision tree algorithms.

##### Abstract (translated by Google)
传统的决策树具有许多有利的特性，包括可解释性，小的计算足迹和从少量训练数据中学习的能力。然而，他们缺乏帮助推动深度学习革命的关键素质：端到端的可训练性，以及从头开始学习那些最能解决给定监督学习问题的特征。最近的工作（Kontschieder 2015）已​​经解决了这个缺陷，但是以损失决策树的主要吸引力特征为代价：事实是每个样本仅沿着树节点的一个小子集被路由。我们在这里提出了一个模型和期望最大化训练方案，在训练时间是完全概率的决策树，但是在确定性退火过程在测试时间变成确定性之后。我们还分析了在图像数据集上学习的斜分裂参数，并且表明可以在每个分裂节点处训练神经网络。总之，我们提出了确定性决策树的第一个端到端的学习方案，并且与公布的标准的倾斜决策树算法相比，或者更高。

##### URL
[http://arxiv.org/abs/1712.02743](http://arxiv.org/abs/1712.02743)

##### PDF
[http://arxiv.org/pdf/1712.02743](http://arxiv.org/pdf/1712.02743)

