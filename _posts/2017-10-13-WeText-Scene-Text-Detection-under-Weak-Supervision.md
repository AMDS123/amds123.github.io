---
layout: post
title: "WeText: Scene Text Detection under Weak Supervision"
date: 2017-10-13 07:08:43
categories: arXiv_CV
tags: arXiv_CV Object_Detection Weakly_Supervised Deep_Learning Detection
author: Shangxuan Tian, Shijian Lu, Chongshou Li
mathjax: true
---

* content
{:toc}

##### Abstract
The requiring of large amounts of annotated training data has become a common constraint on various deep learning systems. In this paper, we propose a weakly supervised scene text detection method (WeText) that trains robust and accurate scene text detection models by learning from unannotated or weakly annotated data. With a "light" supervised model trained on a small fully annotated dataset, we explore semi-supervised and weakly supervised learning on a large unannotated dataset and a large weakly annotated dataset, respectively. For the unsupervised learning, the light supervised model is applied to the unannotated dataset to search for more character training samples, which are further combined with the small annotated dataset to retrain a superior character detection model. For the weakly supervised learning, the character searching is guided by high-level annotations of words/text lines that are widely available and also much easier to prepare. In addition, we design an unified scene character detector by adapting regression based deep networks, which greatly relieves the error accumulation issue that widely exists in most traditional approaches. Extensive experiments across different unannotated and weakly annotated datasets show that the scene text detection performance can be clearly boosted under both scenarios, where the weakly supervised learning can achieve the state-of-the-art performance by using only 229 fully annotated scene text images.

##### Abstract (translated by Google)
大量的注释训练数据的需求已成为各种深度学习系统的共同约束。在本文中，我们提出了一种弱监督的场景文本检测方法（WeText），它通过从未注释或弱注释数据中学习来训练健壮和准确的场景文本检测模型。通过在一个小的完全注释的数据集上训练的“轻量级”监督模型，我们分别在一个大的unannotated数据集和一个大的弱注释的数据集上探索半监督和弱监督学习。对于无监督学习，将光监督模型应用于未注释的数据集，以搜索更多的字符训练样本，再与小注释数据集进行组合，以重新训练出优秀的字符检测模型。对于弱监督的学习，人物搜索是通过广泛使用的词汇/文本行的高级注释来指导的，而且也容易准备。此外，我们设计了一个统一的场景特征检测器，通过适应基于回归的深度网络，大大缓解了大多数传统方法中广泛存在的错误积累问题。跨不同的未注释和弱注释的数据集进行的大量实验表明，在两种场景下，场景文本检测性能都可以得到明显的提升，弱监督学习可以通过仅使用229个完全注释的场景文本图像来实现最先进的性能。

##### URL
[https://arxiv.org/abs/1710.04826](https://arxiv.org/abs/1710.04826)

##### PDF
[https://arxiv.org/pdf/1710.04826](https://arxiv.org/pdf/1710.04826)

