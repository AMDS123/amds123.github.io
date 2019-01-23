---
layout: post
title: "Learning Graph Pooling and Hybrid Convolutional Operations for Text Representations"
date: 2019-01-21 15:35:43
categories: arXiv_AI
tags: arXiv_AI CNN Deep_Learning
author: Hongyang Gao, Yongjun Chen, Shuiwang Ji
mathjax: true
---

* content
{:toc}

##### Abstract
With the development of graph convolutional networks (GCN), deep learning methods have started to be used on graph data. In additional to convolutional layers, pooling layers are another important components of deep learning. However, no effective pooling methods have been developed for graphs currently. In this work, we propose the graph pooling (gPool) layer, which employs a trainable projection vector to measure the importance of nodes in graphs. By selecting the k-most important nodes to form the new graph, gPool achieves the same objective as regular max pooling layers operating on images. Another limitation of GCN when used on graph-based text representation tasks is that, GCNs do not consider the order information of nodes in graph. To address this limitation, we propose the hybrid convolutional (hConv) layer that combines GCN and regular convolutional operations. The hConv layer is capable of increasing receptive fields quickly and computing features automatically. Based on the proposed gPool and hConv layers, we develop new deep networks for text categorization tasks. Our results show that the networks based on gPool and hConv layers achieves new state-of-the-art performance as compared to baseline methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.06965](http://arxiv.org/abs/1901.06965)

##### PDF
[http://arxiv.org/pdf/1901.06965](http://arxiv.org/pdf/1901.06965)

