---
layout: post
title: "Learning without Forgetting"
date: 2017-02-14 22:32:30
categories: arXiv_CV
tags: arXiv_CV CNN
author: Zhizhong Li, Derek Hoiem
mathjax: true
---

* content
{:toc}

##### Abstract
When building a unified vision system or gradually adding new capabilities to a system, the usual assumption is that training data for all tasks is always available. However, as the number of tasks grows, storing and retraining on such data becomes infeasible. A new problem arises where we add new capabilities to a Convolutional Neural Network (CNN), but the training data for its existing capabilities are unavailable. We propose our Learning without Forgetting method, which uses only new task data to train the network while preserving the original capabilities. Our method performs favorably compared to commonly used feature extraction and fine-tuning adaption techniques and performs similarly to multitask learning that uses original task data we assume unavailable. A more surprising observation is that Learning without Forgetting may be able to replace fine-tuning with similar old and new task datasets for improved new task performance.

##### Abstract (translated by Google)
在建立一个统一的视觉系统或逐渐向系统添加新的功能时，通常的假设是所有任务的训练数据总是可用的。然而，随着任务数量的增长，对这些数据的存储和再培训变得不可行。在卷积神经网络（CNN）增加新功能的时候出现了一个新的问题，但是现有功能的训练数据是不可用的。我们提出了我们的无忘记学习方法，它只使用新的任务数据来训练网络，同时保留原有的能力。与通常使用的特征提取和微调适应技术相比，我们的方法性能优越，并且与使用我们假设不可用的原始任务数据的多任务学习类似。一个更令人惊讶的发现是没有遗忘的学习可能能够用相似的旧的和新的任务数据集取代微调来提高新的任务性能。

##### URL
[https://arxiv.org/abs/1606.09282](https://arxiv.org/abs/1606.09282)

##### PDF
[https://arxiv.org/pdf/1606.09282](https://arxiv.org/pdf/1606.09282)

