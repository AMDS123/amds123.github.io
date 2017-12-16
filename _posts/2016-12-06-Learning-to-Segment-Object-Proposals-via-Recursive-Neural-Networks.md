---
layout: post
title: "Learning to Segment Object Proposals via Recursive Neural Networks"
date: 2016-12-06 07:02:41
categories: arXiv_CV
tags: arXiv_CV Object_Detection Inference RNN Prediction Detection
author: Tianshui Chen, Liang Lin, Xian Wu, Xiaonan Luo
mathjax: true
---

* content
{:toc}

##### Abstract
To avoid the exhaustive search over locations and scales, current state-of-the-art object detection systems usually involve a crucial component generating a batch of candidate object proposals from images. In this paper, we present a simple yet effective approach for segmenting object proposals via a deep architecture of recursive neural networks (RNNs), which hierarchically groups regions for detecting object candidates over scales. Unlike traditional methods that mainly adopt fixed similarity measures for merging regions or finding object proposals, our approach adaptively learns the region merging similarity and the objectness measure during the process of hierarchical region grouping. Specifically, guided by a structured loss, the RNN model jointly optimizes the cross-region similarity metric with the region merging process as well as the objectness prediction. During inference of the object proposal generation, we introduce randomness into the greedy search to cope with the ambiguity of grouping regions. Extensive experiments on standard benchmarks, e.g., PASCAL VOC and ImageNet, suggest that our approach is capable of producing object proposals with high recall while well preserving the object boundaries and outperforms other existing methods in both accuracy and efficiency.

##### Abstract (translated by Google)
为了避免对位置和尺度进行详尽的搜索，当前的最新对象检测系统通常包括从图像中生成一批候选对象提议的关键组件。在本文中，我们提出了一种简单而有效的方法，通过递归神经网络（RNN）的深层架构对对象提议进行分割。与传统的主要采用固定相似性度量方法合并区域或找到对象提议的方法不同，我们的方法自适应地学习了分层区域分组过程中的区域合并相似度和对象度量。具体而言，RNN模型以结构化损失为指导，结合区域合并过程和对象预测，共同优化跨区域相似性度量。在对象建议生成的推理过程中，我们将随机性引入到贪婪搜索中，以应对分组区域的模糊性。标准基准测试（例如PASCAL VOC和ImageNet）的大量实验表明，我们的方法能够生成具有高回忆率的对象建议，同时保持对象边界并且在准确性和效率方面优于其他现有方法。

##### URL
[https://arxiv.org/abs/1612.01057](https://arxiv.org/abs/1612.01057)

##### PDF
[https://arxiv.org/pdf/1612.01057](https://arxiv.org/pdf/1612.01057)

