---
layout: post
title: "Rethinking the Inception Architecture for Computer Vision"
date: 2015-12-11 20:27:50
categories: arXiv_CV
tags: arXiv_CV Regularization CNN Inference Classification
author: Christian Szegedy, Vincent Vanhoucke, Sergey Ioffe, Jonathon Shlens, Zbigniew Wojna
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional networks are at the core of most state-of-the-art computer vision solutions for a wide variety of tasks. Since 2014 very deep convolutional networks started to become mainstream, yielding substantial gains in various benchmarks. Although increased model size and computational cost tend to translate to immediate quality gains for most tasks (as long as enough labeled data is provided for training), computational efficiency and low parameter count are still enabling factors for various use cases such as mobile vision and big-data scenarios. Here we explore ways to scale up networks in ways that aim at utilizing the added computation as efficiently as possible by suitably factorized convolutions and aggressive regularization. We benchmark our methods on the ILSVRC 2012 classification challenge validation set demonstrate substantial gains over the state of the art: 21.2% top-1 and 5.6% top-5 error for single frame evaluation using a network with a computational cost of 5 billion multiply-adds per inference and with using less than 25 million parameters. With an ensemble of 4 models and multi-crop evaluation, we report 3.5% top-5 error on the validation set (3.6% error on the test set) and 17.3% top-1 error on the validation set.

##### Abstract (translated by Google)
卷积网络是大多数最先进的计算机视觉解决方案的核心，用于各种任务。自2014年以来，非常深的卷积网络开始成为主流，在各种基准测试中取得了实质性的进展。尽管增加的模型尺寸和计算成本倾向于转化为大多数任务的直接质量收益（只要提供足够的标记数据用于训练），但是计算效率和低参数计数仍然是各种用例如移动视觉和大数据场景。在这里，我们探索如何扩大网络的方式，旨在通过适当分解卷积和积极正则化，尽可能有效地利用增加的计算。我们在ILSVRC 2012分类挑战验证集上对我们的方法进行了基准测试，结果表明：使用计算成本为50亿次的网络，单帧评估的前21％和前5％误差分别为前者的21.2％增加了每个推断和使用少于25万个参数。对于4个模型和多作物评估的集合，我们报告验证集（测试集上的3.6％的错误）的3.5％前5个错误和验证集上17.3％的前1个错误。

##### URL
[https://arxiv.org/abs/1512.00567](https://arxiv.org/abs/1512.00567)

##### PDF
[https://arxiv.org/pdf/1512.00567](https://arxiv.org/pdf/1512.00567)

