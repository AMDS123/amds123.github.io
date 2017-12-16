---
layout: post
title: "Interpreting CNN Knowledge via an Explanatory Graph"
date: 2017-11-22 02:29:51
categories: arXiv_CV
tags: arXiv_CV Knowledge Relation
author: Quanshi Zhang, Ruiming Cao, Feng Shi, Ying Nian Wu, Song-Chun Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
This paper learns a graphical model, namely an explanatory graph, which reveals the knowledge hierarchy hidden inside a pre-trained CNN. Considering that each filter in a conv-layer of a pre-trained CNN usually represents a mixture of object parts, we propose a simple yet efficient method to automatically disentangles different part patterns from each filter, and construct an explanatory graph. In the explanatory graph, each node represents a part pattern, and each edge encodes co-activation relationships and spatial relationships between patterns. More importantly, we learn the explanatory graph for a pre-trained CNN in an unsupervised manner, i.e., without a need of annotating object parts. Experiments show that each graph node consistently represents the same object part through different images. We transfer part patterns in the explanatory graph to the task of part localization, and our method significantly outperforms other approaches.

##### Abstract (translated by Google)
本文学习一个图形模型，即一个解释图，它揭示隐藏在预先训练的CNN内部的知识层次。考虑到预先训练的CNN的一个conv-layer中的每个滤波器通常表示一个对象部分的混合，我们提出了一个简单而有效的方法来自动分解来自每个滤波器的不同部分模式，并构造一个解释图。在说明图中，每个节点表示一个部分模式，每个边编码模式之间的共激活关系和空间关系。更重要的是，我们以无监督的方式学习预先训练的CNN的解释图，即不需要注释对象部分。实验表明，每个图形节点通过不同的图像一致地表示相同的对象部分。我们将解释图中的零件模式转移到零件定位任务中，而且我们的方法明显优于其他方法。

##### URL
[https://arxiv.org/abs/1708.01785](https://arxiv.org/abs/1708.01785)

##### PDF
[https://arxiv.org/pdf/1708.01785](https://arxiv.org/pdf/1708.01785)

