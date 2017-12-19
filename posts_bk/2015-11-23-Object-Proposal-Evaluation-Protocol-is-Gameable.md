---
layout: post
title: "Object-Proposal Evaluation Protocol is 'Gameable'"
date: 2015-11-23 07:16:16
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Neelima Chavali, Harsh Agrawal, Aroma Mahendru, Dhruv Batra
mathjax: true
---

* content
{:toc}

##### Abstract
Object proposals have quickly become the de-facto pre-processing step in a number of vision pipelines (for object detection, object discovery, and other tasks). Their performance is usually evaluated on partially annotated datasets. In this paper, we argue that the choice of using a partially annotated dataset for evaluation of object proposals is problematic -- as we demonstrate via a thought experiment, the evaluation protocol is 'gameable', in the sense that progress under this protocol does not necessarily correspond to a "better" category independent object proposal algorithm. To alleviate this problem, we: (1) Introduce a nearly-fully annotated version of PASCAL VOC dataset, which serves as a test-bed to check if object proposal techniques are overfitting to a particular list of categories. (2) Perform an exhaustive evaluation of object proposal methods on our introduced nearly-fully annotated PASCAL dataset and perform cross-dataset generalization experiments; and (3) Introduce a diagnostic experiment to detect the bias capacity in an object proposal algorithm. This tool circumvents the need to collect a densely annotated dataset, which can be expensive and cumbersome to collect. Finally, we plan to release an easy-to-use toolbox which combines various publicly available implementations of object proposal algorithms which standardizes the proposal generation and evaluation so that new methods can be added and evaluated on different datasets. We hope that the results presented in the paper will motivate the community to test the category independence of various object proposal methods by carefully choosing the evaluation protocol.

##### Abstract (translated by Google)
对象提议很快成为许多视觉流水线（用于对象检测，对象发现和其他任务）中事实上的预处理步骤。他们的表现通常在部分注释的数据集上进行评估。在本文中，我们认为使用部分注释的数据集来评估对象提议的选择是有问题的 - 正如我们通过思想实验所表明的那样，评估协议是“可游戏的”，在这个协议下的进展并不必然对应于“更好”的类别独立对象提议算法。为了缓解这个问题，我们：（1）引入一个几乎完全注释的PASCAL VOC数据集版本，作为一个测试平台来检查对象提议技术是否过度适用于特定的类别列表。 （2）对我们引入的几乎完全注释的PASCAL数据集进行对象建议方法的详尽评估，并进行跨数据集泛化实验; （3）引入诊断实验来检测对象提议算法中的偏差容量。这个工具避免了收集密集注释的数据集的需要，这可能是昂贵和繁琐的收集。最后，我们计划发布一个易于使用的工具箱，该工具箱结合了各种公开提供的对象提议算法的实现，这些算法对提案生成和评估进行标准化，以便可以在不同的数据集上添加和评估新的方法。我们希望通过仔细选择评估协议，本文提出的结果将激励社区测试各种对象提议方法的类别独立性。

##### URL
[https://arxiv.org/abs/1505.05836](https://arxiv.org/abs/1505.05836)

##### PDF
[https://arxiv.org/pdf/1505.05836](https://arxiv.org/pdf/1505.05836)

