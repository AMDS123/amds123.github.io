---
layout: post
title: "Adversarial Binary Coding for Efficient Person Re-identification"
date: 2018-03-29 03:24:06
categories: arXiv_CV
tags: arXiv_CV Re-identification Adversarial Attention Person_Re-identification Optimization
author: Zheng Liu, Jie Qin, Annan Li, Yunhong Wang, Luc Van Gool
mathjax: true
---

* content
{:toc}

##### Abstract
Person re-identification (ReID) aims at matching persons across different views/scenes. In addition to accuracy, the matching efficiency has received more and more attention because of demanding applications using large-scale data. Several binary coding based methods have been proposed for efficient ReID, which either learn projections to map high-dimensional features to compact binary codes, or directly adopt deep neural networks by simply inserting an additional fully-connected layer with tanh-like activations. However, the former approach requires time-consuming hand-crafted feature extraction and complicated (discrete) optimizations; the latter lacks the necessary discriminative information greatly due to the straightforward activation functions. In this paper, we propose a simple yet effective framework for efficient ReID inspired by the recent advances in adversarial learning. Specifically, instead of learning explicit projections or adding fully-connected mapping layers, the proposed Adversarial Binary Coding (ABC) framework guides the extraction of binary codes implicitly and effectively. The discriminability of the extracted codes is further enhanced by equipping the ABC with a deep triplet network for the ReID task. More importantly, the ABC and triplet network are simultaneously optimized in an end-to-end manner. Extensive experiments on three large-scale ReID benchmarks demonstrate the superiority of our approach over the state-of-the-art methods.

##### Abstract (translated by Google)
人员重新识别（ReID）旨在匹配不同视图/场景的人员。除了精度之外，由于使用大规模数据的要求苛刻的应用，匹配效率已经受到越来越多的关注。已经提出了几种基于二进制编码的方法用于有效的ReID，其要么学习将高维特征映射为紧缩二进制代码的投影，要么通过简单地插入附加的完全连接层和类似tanh的激活直接采用深度神经网络。然而，前一种方法需要耗时的手工特征提取和复杂（离散）优化;由于直接激活功能，后者缺乏必要的区分信息。在本文中，我们提出了一个简单而有效的ReID框架，该框架受对手学习近期进展的启发启发。具体而言，所提出的对抗二进制编码（ABC）框架并非学习明确的投影或添加完全连接的映射层，而是隐式且有效地指导提取二进制代码。通过为ABC Reid任务配备深度三重网络，进一步提高了提取代码的可区分性。更重要的是，ABC和三重网络同时以端到端的方式进行了优化。在三个大型ReID基准上的大量实验证明了我们的方法优于最先进的方法的优越性。

##### URL
[http://arxiv.org/abs/1803.10914](http://arxiv.org/abs/1803.10914)

##### PDF
[http://arxiv.org/pdf/1803.10914](http://arxiv.org/pdf/1803.10914)

