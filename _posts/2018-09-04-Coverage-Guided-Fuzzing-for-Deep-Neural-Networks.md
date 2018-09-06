---
layout: post
title: "Coverage-Guided Fuzzing for Deep Neural Networks"
date: 2018-09-04 23:07:45
categories: arXiv_AI
tags: arXiv_AI
author: Xiaofei Xie, Lei Ma, Felix Juefei-Xu, Hongxu Chen, Minhui Xue, Bo Li, Yang Liu, Jianjun Zhao, Jianxiong Yin, Simon See
mathjax: true
---

* content
{:toc}

##### Abstract
In company with the data explosion over the past decade, deep neural network (DNN) based software has experienced unprecedented leap and is becoming the key driving force of many novel industrial applications, including many safety-critical scenarios such as autonomous driving. Despite great success achieved in various human intelligence tasks, similar to traditional software, DNNs could also exhibit incorrect behaviors caused by hidden defects causing severe accidents and losses. In this paper, we propose an automated fuzz testing framework for hunting potential defects of general-purpose DNNs. It performs metamorphic mutation to generate new semantically preserved tests, and leverages multiple plugable coverage criteria as feedback to guide the test generation from different perspectives. To be scalable towards practical-sized DNNs, our framework maintains tests in batch, and prioritizes the tests selection based on active feedback. The effectiveness of our framework is extensively investigated on 3 popular datasets (MNIST, CIFAR-10, ImageNet) and 7 DNNs with diverse complexities, under large set of 6 coverage criteria as feedback. The large-scale experiments demonstrate that our fuzzing framework can (1) significantly boost the coverage with guidance; (2) generate useful tests to detect erroneous behaviors and facilitate the DNN model quality evaluation; (3) accurately capture potential defects during DNN quantization for platform migration.

##### Abstract (translated by Google)
随着过去十年数据爆炸，基于深度神经网络（DNN）的软件经历了前所未有的飞跃，并且正在成为许多新型工业应用的关键驱动力，包括许多安全关键场景，如自动驾驶。尽管在各种人类情报任务中取得了巨大成功，但与传统软件类似，DNN也可能表现出由隐藏缺陷导致严重事故和损失的错误行为。在本文中，我们提出了一种自动模糊测试框架，用于搜索通用DNN的潜在缺陷。它执行变形突变以生成新的语义保留测试，并利用多个可插入覆盖标准作为反馈，从不同角度指导测试生成。为了可扩展到实用大小的DNN，我们的框架可以批量维护测试，并根据主动反馈确定测试选择的优先级。我们的框架的有效性在3个流行的数据集（MNIST，CIFAR-10，ImageNet）和7个具有不同复杂性的DNN上进行了广泛的研究，其中大量的6个覆盖标准作为反馈。大规模实验表明，我们的模糊测试框架可以（1）在指导下显着提高覆盖范围; （2）生成有用的测试以检测错误行为并促进DNN模型质量评估; （3）在平台迁移的DNN量化过程中准确捕获潜在缺陷。

##### URL
[http://arxiv.org/abs/1809.01266](http://arxiv.org/abs/1809.01266)

##### PDF
[http://arxiv.org/pdf/1809.01266](http://arxiv.org/pdf/1809.01266)

