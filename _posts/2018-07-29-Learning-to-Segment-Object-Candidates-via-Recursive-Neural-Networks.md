---
layout: post
title: "Learning to Segment Object Candidates via Recursive Neural Networks"
date: 2018-07-29 02:17:35
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


##### URL
[https://arxiv.org/abs/1612.01057](https://arxiv.org/abs/1612.01057)

##### PDF
[https://arxiv.org/pdf/1612.01057](https://arxiv.org/pdf/1612.01057)

