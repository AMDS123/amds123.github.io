---
layout: post
title: "Integral Curvature Representation and Matching Algorithms for Identification of Dolphins and Whales"
date: 2017-08-25 15:44:46
categories: arXiv_CV
tags: arXiv_CV
author: Hendrik J. Weideman, Zachary M. Jablons, Jason Holmberg, Kiirsten Flynn, John Calambokidis, Reny B. Tyson, Jason B. Allen, Randall S. Wells, Krista Hupman, Kim Urian, Charles V. Stewart
mathjax: true
---

* content
{:toc}

##### Abstract
We address the problem of identifying individual cetaceans from images showing the trailing edge of their fins. Given the trailing edge from an unknown individual, we produce a ranking of known individuals from a database. The nicks and notches along the trailing edge define an individual's unique signature. We define a representation based on integral curvature that is robust to changes in viewpoint and pose, and captures the pattern of nicks and notches in a local neighborhood at multiple scales. We explore two ranking methods that use this representation. The first uses a dynamic programming time-warping algorithm to align two representations, and interprets the alignment cost as a measure of similarity. This algorithm also exploits learned spatial weights to downweight matches from regions of unstable curvature. The second interprets the representation as a feature descriptor. Feature keypoints are defined at the local extrema of the representation. Descriptors for the set of known individuals are stored in a tree structure, which allows us to perform queries given the descriptors from an unknown trailing edge. We evaluate the top-k accuracy on two real-world datasets to demonstrate the effectiveness of the curvature representation, achieving top-1 accuracy scores of approximately 95% and 80% for bottlenose dolphins and humpback whales, respectively.

##### Abstract (translated by Google)
我们解决了从显示翅片后缘的图像中识别出个别鲸目动物的问题。考虑到来自未知个体的后沿，我们从数据库中产生已知个体的排名。后缘的缺口和缺口定义了个人的独特签名。我们定义了一个基于积分曲率的表示，它对于视点和姿态的变化是鲁棒的，并且在多个尺度上捕捉局部邻域中的刻痕和刻痕的模式。我们探索两种使用这种表示的排序方法。第一个使用动态规划时间规整算法来对齐两个表示，并将对齐成本解释为相似度的度量。该算法还利用学习的空间权重来减轻不稳定曲率区域的匹配。第二个解释表示为特征描述符。特征关键点在表示的局部极值处定义。已知个体的描述符被存储在树形结构中，这允许我们在给定来自未知后沿的描述符的情况下执行查询。我们评估两个真实世界数据集上的top-k准确性，以证明曲率表示的有效性，分别为宽吻海豚和驼背鲸实现了约95％和80％的前1精度分数。

##### URL
[https://arxiv.org/abs/1708.07785](https://arxiv.org/abs/1708.07785)

##### PDF
[https://arxiv.org/pdf/1708.07785](https://arxiv.org/pdf/1708.07785)

