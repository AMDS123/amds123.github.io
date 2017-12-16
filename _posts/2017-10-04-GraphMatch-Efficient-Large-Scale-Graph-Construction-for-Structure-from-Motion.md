---
layout: post
title: "GraphMatch: Efficient Large-Scale Graph Construction for Structure from Motion"
date: 2017-10-04 13:45:00
categories: arXiv_CV
tags: arXiv_CV
author: Qiaodong Cui, Victor Fragoso, Chris Sweeney, Pradeep Sen
mathjax: true
---

* content
{:toc}

##### Abstract
We present GraphMatch, an approximate yet efficient method for building the matching graph for large-scale structure-from-motion (SfM) pipelines. Unlike modern SfM pipelines that use vocabulary (Voc.) trees to quickly build the matching graph and avoid a costly brute-force search of matching image pairs, GraphMatch does not require an expensive offline pre-processing phase to construct a Voc. tree. Instead, GraphMatch leverages two priors that can predict which image pairs are likely to match, thereby making the matching process for SfM much more efficient. The first is a score computed from the distance between the Fisher vectors of any two images. The second prior is based on the graph distance between vertices in the underlying matching graph. GraphMatch combines these two priors into an iterative "sample-and-propagate" scheme similar to the PatchMatch algorithm. Its sampling stage uses Fisher similarity priors to guide the search for matching image pairs, while its propagation stage explores neighbors of matched pairs to find new ones with a high image similarity score. Our experiments show that GraphMatch finds the most image pairs as compared to competing, approximate methods while at the same time being the most efficient.

##### Abstract (translated by Google)
我们提出了GraphMatch，一种近似而有效的方法，用于构建大规模动态结构（SfM）管线的匹配图。与使用词汇（Voc。）树快速构建匹配图并避免成本高昂的匹配图像对的蛮力搜索的现代SfM管线不同，GraphMatch不需要昂贵的离线预处理阶段来构建Voc。树。相反，GraphMatch利用两个可以预测哪些图像对可能匹配的先验，从而使SfM的匹配过程更有效率。第一个是根据任意两个图像的Fisher矢量之间的距离计算得分。第二个先验是基于底层匹配图中顶点之间的图距。 GraphMatch将这两个先验结合成一个类似于PatchMatch算法的迭代“采样和传播”方案。其采样阶段使用Fisher相似度先验来指导匹配图像对的搜索，而其传播阶段探索匹配对的邻居以找到具有高图像相似度得分的新图像对。我们的实验显示，与竞争的近似方法相比，GraphMatch找到最多的图像对，同时效率最高。

##### URL
[https://arxiv.org/abs/1710.01602](https://arxiv.org/abs/1710.01602)

##### PDF
[https://arxiv.org/pdf/1710.01602](https://arxiv.org/pdf/1710.01602)

