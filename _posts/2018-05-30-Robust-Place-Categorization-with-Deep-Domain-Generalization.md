---
layout: post
title: "Robust Place Categorization with Deep Domain Generalization"
date: 2018-05-30 16:00:34
categories: arXiv_RO
tags: arXiv_RO CNN Classification Deep_Learning
author: Massimiliano Mancini, Samuel Rota Bul&#xf2;, Barbara Caputo, Elisa Ricci
mathjax: true
---

* content
{:toc}

##### Abstract
Traditional place categorization approaches in robot vision assume that training and test images have similar visual appearance. Therefore, any seasonal, illumination and environmental changes typically lead to severe degradation in performance. To cope with this problem, recent works have proposed to adopt domain adaptation techniques. While effective, these methods assume that some prior information about the scenario where the robot will operate is available at training time. Unfortunately, in many cases this assumption does not hold, as we often do not know where a robot will be deployed. To overcome this issue, in this paper we present an approach which aims at learning classification models able to generalize to unseen scenarios. Specifically, we propose a novel deep learning framework for domain generalization. Our method develops from the intuition that, given a set of different classification models associated to known domains (e.g. corresponding to multiple environments, robots), the best model for a new sample in the novel domain can be computed directly at test time by optimally combining the known models. To implement our idea, we exploit recent advances in deep domain adaptation and design a Convolutional Neural Network architecture with novel layers performing a weighted version of Batch Normalization. Our experiments, conducted on three common datasets for robot place categorization, confirm the validity of our contribution.

##### Abstract (translated by Google)
机器人视觉中的传统场所分类方法假设训练和测试图像具有相似的视觉外观。因此，任何季节性，光照和环境变化通常会导致性能严重下降。为了解决这个问题，最近的工作已经提出采用领域适应技术。虽然有效，但这些方法假定在训练时间可获得关于机器人将运行场景的一些先前信息。不幸的是，在许多情况下，这个假设并不成立，因为我们通常不知道机器人的部署位置。为了克服这个问题，在本文中，我们提出了一种方法，旨在学习能够推广到看不见场景的分类模型。具体来说，我们提出了一个新的领域概括深度学习框架。我们的方法从直觉开始，即给定与已知域（例如，对应于多个环境，机器人）相关的一组不同的分类模型（例如，对应于多个环境，机器人），可以在测试时间通过最优地组合来直接计算新域中的新样本的最佳模型已知的模型。为了实现我们的想法，我们利用最近在深度域适应方面的进展，并设计了具有执行加权版本的批量标准化的新层的卷积神经网络体系结构。我们在三个常见的机器人地点分类数据集上进行的实验证实了我们贡献的有效性。

##### URL
[http://arxiv.org/abs/1805.12048](http://arxiv.org/abs/1805.12048)

##### PDF
[http://arxiv.org/pdf/1805.12048](http://arxiv.org/pdf/1805.12048)

