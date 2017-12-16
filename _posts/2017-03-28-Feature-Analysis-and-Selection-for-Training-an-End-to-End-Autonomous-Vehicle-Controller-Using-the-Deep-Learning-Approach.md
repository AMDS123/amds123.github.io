---
layout: post
title: "Feature Analysis and Selection for Training an End-to-End Autonomous Vehicle Controller Using the Deep Learning Approach"
date: 2017-03-28 18:52:38
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Shun Yang, Wenshuo Wang, Chang Liu, Kevin Deng, J. Karl Hedrick
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning-based approaches have been widely used for training controllers for autonomous vehicles due to their powerful ability to approximate nonlinear functions or policies. However, the training process usually requires large labeled data sets and takes a lot of time. In this paper, we analyze the influences of features on the performance of controllers trained using the convolutional neural networks (CNNs), which gives a guideline of feature selection to reduce computation cost. We collect a large set of data using The Open Racing Car Simulator (TORCS) and classify the image features into three categories (sky-related, roadside-related, and road-related features).We then design two experimental frameworks to investigate the importance of each single feature for training a CNN controller.The first framework uses the training data with all three features included to train a controller, which is then tested with data that has one feature removed to evaluate the feature's effects. The second framework is trained with the data that has one feature excluded, while all three features are included in the test data. Different driving scenarios are selected to test and analyze the trained controllers using the two experimental frameworks. The experiment results show that (1) the road-related features are indispensable for training the controller, (2) the roadside-related features are useful to improve the generalizability of the controller to scenarios with complicated roadside information, and (3) the sky-related features have limited contribution to train an end-to-end autonomous vehicle controller.

##### Abstract (translated by Google)
基于深度学习的方法由于具有逼近非线性函数或策略的强大能力，已被广泛用于自主车辆的训练控制器。但是，训练过程通常需要大量标记的数据集并花费大量时间。本文分析了特征对卷积神经网络（CNNs）训练的控制器性能的影响，给出了特征选择的指导原则，以降低计算量。我们使用Open Racing Car Simulator（TORCS）收集大量数据，并将图像特征分为三类（天空相关，路边相关和道路相关的特征）。然后我们设计两个实验框架来研究重要性用于训练CNN控制器的每个单个特征。第一个框架使用包含所有三个特征的训练数据来训练控制器，然后使用去除了一个特征的数据对其进行测试以评估特征的效果。第二个框架是用排除了一个特征的数据进行训练的，而所有三个特征都包含在测试数据中。选择不同的驾驶场景来使用两个实验框架来测试和分析训练有素的控制器。实验结果表明：（1）道路相关特征对训练控制器是必不可少的;（2）路边相关特征有助于提高控制器对复杂路况信息情景的普遍性;（3）天空相关的特征对于培养端到端的自主车辆控制器的贡献有限。

##### URL
[https://arxiv.org/abs/1703.09744](https://arxiv.org/abs/1703.09744)

##### PDF
[https://arxiv.org/pdf/1703.09744](https://arxiv.org/pdf/1703.09744)

