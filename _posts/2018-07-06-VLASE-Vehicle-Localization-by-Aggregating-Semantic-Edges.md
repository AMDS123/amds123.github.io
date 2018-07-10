---
layout: post
title: "VLASE: Vehicle Localization by Aggregating Semantic Edges"
date: 2018-07-06 18:15:06
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval
author: Xin Yu, Sagar Chaturvedi, Chen Feng, Yuichi Taguchi, Teng-Yok Lee, Clinton Fernandes, Srikumar Ramalingam
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose VLASE, a framework to use semantic edge features from images to achieve on-road localization. Semantic edge features denote edge contours that separate pairs of distinct objects such as building-sky, road- sidewalk, and building-ground. While prior work has shown promising results by utilizing the boundary between prominent classes such as sky and building using skylines, we generalize this approach to consider semantic edge features that arise from 19 different classes. Our localization algorithm is simple, yet very powerful. We extract semantic edge features using a recently introduced CASENet architecture and utilize VLAD framework to perform image retrieval. Our experiments show that we achieve improvement over some of the state-of-the-art localization algorithms such as SIFT-VLAD and its deep variant NetVLAD. We use ablation study to study the importance of different semantic classes and show that our unified approach achieves better performance compared to individual prominent features such as skylines.

##### Abstract (translated by Google)
在本文中，我们提出了VLASE，一个使用图像语义边缘特征来实现路上定位的框架。语义边缘特征表示边缘轮廓，其分离成对的不同对象，例如建筑物 - 天空，道路 - 人行道和建筑物 - 地面。虽然先前的工作通过利用天空和使用天际线的建筑等突出类之间的边界显示出有希望的结果，但我们推广这种方法来考虑由19个不同类产生的语义边缘特征。我们的本地化算法很简单，但功能非常强大。我们使用最近引入的CASENet架构提取语义边缘特征，并利用VLAD框架来执行图像检索。我们的实验表明，我们实现了对一些最先进的定位算法的改进，例如SIFT-VLAD及其深层变体NetVLAD。我们使用消融研究来研究不同语义类别的重要性，并表明我们的统一方法与单个突出特征（如天际线）相比可以获得更好的性能。

##### URL
[http://arxiv.org/abs/1807.02536](http://arxiv.org/abs/1807.02536)

##### PDF
[http://arxiv.org/pdf/1807.02536](http://arxiv.org/pdf/1807.02536)

