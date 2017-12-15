---
layout: post
title: "Enlightening Deep Neural Networks with Knowledge of Confounding Factors"
date: 2016-07-08 15:00:11
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN Classification Deep_Learning Recognition
author: Yu Zhong, Gil Ettinger
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning techniques have demonstrated significant capacity in modeling some of the most challenging real world problems of high complexity. Despite the popularity of deep models, we still strive to better understand the underlying mechanism that drives their success. Motivated by observations that neurons in trained deep nets predict attributes indirectly related to the training tasks, we recognize that a deep network learns representations more general than the task at hand to disentangle impacts of multiple confounding factors governing the data, in order to isolate the effects of the concerning factors and optimize a given objective. Consequently, we propose a general framework to augment training of deep models with information on auxiliary explanatory data variables, in an effort to boost this disentanglement and train deep networks that comprehend the data interactions and distributions more accurately, and thus improve their generalizability. We incorporate information on prominent auxiliary explanatory factors of the data population into existing architectures as secondary objective/loss blocks that take inputs from hidden layers during training. Once trained, these secondary circuits can be removed to leave a model with the same architecture as the original, but more generalizable and discerning thanks to its comprehension of data interactions. Since pose is one of the most dominant confounding factors for object recognition, we apply this principle to instantiate a pose-aware deep convolutional neural network and demonstrate that auxiliary pose information indeed improves the classification accuracy in our experiments on SAR target classification tasks.

##### Abstract (translated by Google)
深度学习技术已经证明了在高复杂性的一些最具挑战性的现实世界问题的建模方面的巨大能力。尽管深度模型很受欢迎，但我们仍然力求更好地理解推动其成功的基本机制。受训练深层网络中的神经元预测了与训练任务间接相关的属性，我们认识到，深层网络学习比目前任务更广泛的表示来解决影响多个混杂因素的数据控制，以便隔离效应的相关因素，并优化既定目标。因此，我们提出了一个通用的框架来加强对具有辅助解释性数据变量信息的深层模型的训练，以便加强这种解决方案，并且训练能够更准确地理解数据交互和分布的深层网络，从而提高它们的普遍性。我们将数据总体的主要辅助说明因素的信息纳入现有体系结构，作为在训练期间从隐藏层获取输入的次要目标/损失块。一旦训练完毕，这些二级电路就可以被移除，从而留下一个与原来相同架构的模型，但是由于对数据交互的理解，这个模型更具概括性和辨别力。由于姿态是目标识别中最主要的混杂因素之一，我们应用这个原理来实例化一个姿态感知的深度卷积神经网络，并证明辅助姿态信息确实提高了SAR目标分类任务实验中的分类精度。

##### URL
[https://arxiv.org/abs/1607.02397](https://arxiv.org/abs/1607.02397)

##### PDF
[https://arxiv.org/pdf/1607.02397](https://arxiv.org/pdf/1607.02397)

