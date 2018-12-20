---
layout: post
title: "Explanatory Graphs for CNNs"
date: 2018-12-18 06:33:49
categories: arXiv_CV
tags: arXiv_CV Knowledge GAN Classification Relation
author: Quanshi Zhang, Xin Wang, Ruiming Cao, Ying Nian Wu, Feng Shi, Song-Chun Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces a graphical model, namely an explanatory graph, which reveals the knowledge hierarchy hidden inside conv-layers of a pre-trained CNN. Each filter in a conv-layer of a CNN for object classification usually represents a mixture of object parts. We develop a simple yet effective method to disentangle object-part pattern components from each filter. We construct an explanatory graph to organize the mined part patterns, where a node represents a part pattern, and each edge encodes co-activation relationships and spatial relationships between patterns. More crucially, given a pre-trained CNN, the explanatory graph is learned without a need of annotating object parts. Experiments show that each graph node consistently represented the same object part through different images, which boosted the transferability of CNN features. We transferred part patterns in the explanatory graph to the task of part localization, and our method significantly outperformed other approaches.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.07997](http://arxiv.org/abs/1812.07997)

##### PDF
[http://arxiv.org/pdf/1812.07997](http://arxiv.org/pdf/1812.07997)

