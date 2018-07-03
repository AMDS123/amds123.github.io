---
layout: post
title: "Learning to Segment Object Candidates via Recursive Neural Networks"
date: 2018-07-02 09:02:27
categories: arXiv_CV
tags: arXiv_CV Object_Detection Inference Prediction Detection
author: Tianshui Chen, Liang Lin, Xian Wu, Nong Xiao, Xiaonan Luo
mathjax: true
---

* content
{:toc}

##### Abstract
To avoid the exhaustive search over locations and scales, current state-of-the-art object detection systems usually involve a crucial component generating a batch of candidate object proposals from images. In this paper, we present a simple yet effective approach for segmenting object proposals via a deep architecture of recursive neural networks (ReNNs), which hierarchically groups regions for detecting object candidates over scales. Unlike traditional methods that mainly adopt fixed similarity measures for merging regions or finding object proposals, our approach adaptively learns the region merging similarity and the objectness measure during the process of hierarchical region grouping. Specifically, guided by a structured loss, the ReNN model jointly optimizes the cross-region similarity metric with the region merging process as well as the objectness prediction. During inference of the object proposal generation, we introduce randomness into the greedy search to cope with the ambiguity of grouping regions. Extensive experiments on standard benchmarks, e.g., PASCAL VOC and ImageNet, suggest that our approach is capable of producing object proposals with high recall while well preserving the object boundaries and outperforms other existing methods in both accuracy and efficiency.

##### Abstract (translated by Google)
为了避免对位置和尺度进行穷举搜索，当前最先进的对象检测系统通常涉及从图像生成一批候选对象提议的关键组件。在本文中，我们提出了一种简单而有效的方法，用于通过递归神经网络（ReNN）的深层体系结构来分割对象提议，该层次结构将用于检测对象候选的区域按比例分组。与主要采用固定相似性度量来合并区域或寻找对象建议的传统方法不同，我们的方法在层次区域分组过程中自适应地学习区域合并相似性和对象度量。具体而言，在结构化损失的引导下，ReNN模型与区域合并过程以及对象性预测共同优化跨区域相似性度量。在推理对象提议生成期间，我们在贪婪搜索中引入随机性以应对分组区域的模糊性。关于标准基准的广泛实验，例如PASCAL VOC和ImageNet，表明我们的方法能够产生具有高召回率的对象提议，同时保持对象边界并在准确性和效率方面优于其他现有方法。

##### URL
[http://arxiv.org/abs/1612.01057](http://arxiv.org/abs/1612.01057)

##### PDF
[http://arxiv.org/pdf/1612.01057](http://arxiv.org/pdf/1612.01057)

