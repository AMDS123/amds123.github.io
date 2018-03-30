---
layout: post
title: "Efficient Interactive Annotation of Segmentation Datasets with Polygon-RNN++"
date: 2018-03-26 16:14:36
categories: arXiv_CV
tags: arXiv_CV Segmentation Reinforcement_Learning RNN
author: David Acuna, Huan Ling, Amlan Kar, Sanja Fidler
mathjax: true
---

* content
{:toc}

##### Abstract
Manually labeling datasets with object masks is extremely time consuming. In this work, we follow the idea of Polygon-RNN to produce polygonal annotations of objects interactively using humans-in-the-loop. We introduce several important improvements to the model: 1) we design a new CNN encoder architecture, 2) show how to effectively train the model with Reinforcement Learning, and 3) significantly increase the output resolution using a Graph Neural Network, allowing the model to accurately annotate high-resolution objects in images. Extensive evaluation on the Cityscapes dataset shows that our model, which we refer to as Polygon-RNN++, significantly outperforms the original model in both automatic (10% absolute and 16% relative improvement in mean IoU) and interactive modes (requiring 50% fewer clicks by annotators). We further analyze the cross-domain scenario in which our model is trained on one dataset, and used out of the box on datasets from varying domains. The results show that Polygon-RNN++ exhibits powerful generalization capabilities, achieving significant improvements over existing pixel-wise methods. Using simple online fine-tuning we further achieve a high reduction in annotation time for new datasets, moving a step closer towards an interactive annotation tool to be used in practice.

##### Abstract (translated by Google)
用对象掩码手动标记数据集非常耗时。在这项工作中，我们遵循Polygon-RNN的思想，使用人在回路中交互式地生成对象的多边形注释。我们对该模型进行了几项重要改进：1）我们设计了一种新的CNN编码器架构，2）展示了如何使用强化学习有效地训练模型，3）使用图形神经网络显着提高输出分辨率，准确地注释图像中的高分辨率对象。对Cityscapes数据集的广泛评估表明，我们的模型（我们称之为Polygon-RNN ++）在自动模式（平均IoU的10％绝对值和16％的相对改善）和交互模式（需要的点击次数减少50％）上明显优于原始模型由注释者）。我们进一步分析了我们的模型在一个数据集上进行训练的跨域场景，并且在不同领域的数据集上开箱即用。结果表明，Polygon-RNN ++具有强大的泛化能力，与现有的逐像素方法相比，显着改进。通过简单的在线微调，我们进一步实现了新数据集注释时间的大幅缩短，向实践中使用的交互式注释工具又迈进了一步。

##### URL
[https://arxiv.org/abs/1803.09693](https://arxiv.org/abs/1803.09693)

##### PDF
[https://arxiv.org/pdf/1803.09693](https://arxiv.org/pdf/1803.09693)

