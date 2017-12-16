---
layout: post
title: "Learning to Compose Domain-Specific Transformations for Data Augmentation"
date: 2017-09-30 04:27:53
categories: arXiv_CV
tags: arXiv_CV Adversarial Relation_Extraction Relation
author: Alexander J. Ratner, Henry R. Ehrenberg, Zeshan Hussain, Jared Dunnmon, Christopher Ré
mathjax: true
---

* content
{:toc}

##### Abstract
Data augmentation is a ubiquitous technique for increasing the size of labeled training sets by leveraging task-specific data transformations that preserve class labels. While it is often easy for domain experts to specify individual transformations, constructing and tuning the more sophisticated compositions typically needed to achieve state-of-the-art results is a time-consuming manual task in practice. We propose a method for automating this process by learning a generative sequence model over user-specified transformation functions using a generative adversarial approach. Our method can make use of arbitrary, non-deterministic transformation functions, is robust to misspecified user input, and is trained on unlabeled data. The learned transformation model can then be used to perform data augmentation for any end discriminative model. In our experiments, we show the efficacy of our approach on both image and text datasets, achieving improvements of 4.0 accuracy points on CIFAR-10, 1.4 F1 points on the ACE relation extraction task, and 3.4 accuracy points when using domain-specific transformation operations on a medical imaging dataset as compared to standard heuristic augmentation approaches.

##### Abstract (translated by Google)
数据增强是一种无处不在的技术，通过利用保留类别标签的任务特定数据转换来增加标记训练集的大小。虽然领域专家通常很容易指定个人转换，但构建和调整通常需要达到最新结果的更复杂的组合是实践中耗时的手动任务。我们提出了一种自动化这个过程的方法，通过使用生成对抗方法学习用户指定的转换函数的生成序列模型。我们的方法可以使用任意的，非确定性的变换函数，对错误指定的用户输入是鲁棒的，并且对未标记的数据进行训练。然后可以使用所学习的转换模型来为任何结束判别模型执行数据增强。在我们的实验中，我们展示了我们的方法在图像和文本数据集上的有效性，实现了CIFAR-10上的4.0个精度点，ACE关系提取任务上的1.4个F1点以及使用特定于领域的转换操作时的3.4个精度点在医学成像数据集相比，标准的启发式增强方法。

##### URL
[https://arxiv.org/abs/1709.01643](https://arxiv.org/abs/1709.01643)

##### PDF
[https://arxiv.org/pdf/1709.01643](https://arxiv.org/pdf/1709.01643)

