---
layout: post
title: "Single Shot TextSpotter with Explicit Alignment and Attention"
date: 2018-03-09 11:30:51
categories: arXiv_CV
tags: arXiv_CV Attention CNN RNN Detection Recognition
author: Tong He, Zhi Tian, Weilin Huang, Chunhua Shen, Yu Qiao, Changming Sun
mathjax: true
---

* content
{:toc}

##### Abstract
Text detection and recognition in natural images have long been considered as two separate tasks that are processed sequentially. Training of two tasks in a unified framework is non-trivial due to significant dif- ferences in optimisation difficulties. In this work, we present a conceptually simple yet efficient framework that simultaneously processes the two tasks in one shot. Our main contributions are three-fold: 1) we propose a novel text-alignment layer that allows it to precisely compute convolutional features of a text instance in ar- bitrary orientation, which is the key to boost the per- formance; 2) a character attention mechanism is introduced by using character spatial information as explicit supervision, leading to large improvements in recognition; 3) two technologies, together with a new RNN branch for word recognition, are integrated seamlessly into a single model which is end-to-end trainable. This allows the two tasks to work collaboratively by shar- ing convolutional features, which is critical to identify challenging text instances. Our model achieves impressive results in end-to-end recognition on the ICDAR2015 dataset, significantly advancing most recent results, with improvements of F-measure from (0.54, 0.51, 0.47) to (0.82, 0.77, 0.63), by using a strong, weak and generic lexicon respectively. Thanks to joint training, our method can also serve as a good detec- tor by achieving a new state-of-the-art detection performance on two datasets.

##### Abstract (translated by Google)
长期以来，自然图像中的文本检测和识别被视为按顺序处理的两个独立任务。由于在优化困难方面存在显着差异，在统一框架下培训两项任务并非微不足道。在这项工作中，我们提出了一个概念简单而高效的框架，可以同时处理两个任务。我们的主要贡献有三个：1）我们提出了一种新颖的文本对齐层，允许它精确地计算文本实例的卷积特征，这是提高性能的关键; 2）将字符空间信息作为显式监督引入角色关注机制，导致识别率大幅度提高; 3）两种技术，连同一个新的RNN分支用于单词识别，可以无缝集成到一个端到端可训练的单一模型中。这允许两个任务通过共享卷积特征来协同工作，这对识别具有挑战性的文本实例至关重要。我们的模型在ICDAR2015数据集的端到端识别方面取得了令人印象深刻的结果，显着推进了最新的结果，F-测量值从（0.54,0.51,0.47）提高到（0.82,0.77,0.63），通过使用强，弱和通用词典分别。通过联合培训，我们的方法可以作为一个好的检测器，通过在两个数据集上实现新的最新检测性能。

##### URL
[http://arxiv.org/abs/1803.03474](http://arxiv.org/abs/1803.03474)

##### PDF
[http://arxiv.org/pdf/1803.03474](http://arxiv.org/pdf/1803.03474)

