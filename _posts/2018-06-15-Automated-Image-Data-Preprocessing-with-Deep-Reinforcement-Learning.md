---
layout: post
title: "Automated Image Data Preprocessing with Deep Reinforcement Learning"
date: 2018-06-15 10:15:10
categories: arXiv_CV
tags: arXiv_CV Reinforcement_Learning
author: Tran Ngoc Minh, Mathieu Sinn, Hoang Thanh Lam, Martin Wistuba
mathjax: true
---

* content
{:toc}

##### Abstract
Data preparation, i.e. the process of transforming raw data into a format that can be used for training effective machine learning models, is a tedious and time-consuming task. For image data, preprocessing typically involves a sequence of basic transformations such as cropping, filtering, rotating or flipping images. Currently, data scientists decide manually based on their experience which transformations to apply in which particular order to a given image data set. Besides constituting a bottleneck in real-world data science projects, manual image data preprocessing may yield suboptimal results as data scientists need to rely on intuition or trial-and-error approaches when exploring the space of possible image transformations and thus might not be able to discover the most effective ones. To mitigate the inefficiency and potential ineffectiveness of manual data preprocessing, this paper proposes a deep reinforcement learning framework to automatically discover the optimal data preprocessing steps for training an image classifier. The framework takes as input sets of labeled images and predefined preprocessing transformations. It jointly learns the classifier and the optimal preprocessing transformations for individual images. Experimental results show that the proposed approach not only improves the accuracy of image classifiers, but also makes them substantially more robust to noisy inputs at test time.

##### Abstract (translated by Google)
数据准备，即将原始数据转换为可用于训练有效机器学习模型的格式的过程是一项繁琐且耗时的任务。对于图像数据，预处理通常涉及一系列基本转换，例如裁剪，过滤，旋转或翻转图像。目前，数据科学家根据他们的经验，手动决定将哪种特定顺序应用于给定图像数据集的转换。除了构成现实世界数据科学项目的瓶颈之外，手动图像数据预处理可能会产生次优的结果，因为数据科学家在探索可能的图像转换空间时需要依靠直觉或反复试验方法，因此可能无法发现最有效的。为了减轻手动数据预处理的低效率和潜在的无效性，本文提出了一个深度强化学习框架来自动发现训练图像分类器的最佳数据预处理步骤。该框架将标记图像和预定义的预处理转换作为输入集合。它共同学习了单个图像的分类器和最优预处理转换。实验结果表明，所提出的方法不仅提高了图像分类器的精度，而且使其在测试时对噪声输入具有更强的鲁棒性。

##### URL
[http://arxiv.org/abs/1806.05886](http://arxiv.org/abs/1806.05886)

##### PDF
[http://arxiv.org/pdf/1806.05886](http://arxiv.org/pdf/1806.05886)

