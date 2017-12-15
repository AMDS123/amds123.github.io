---
layout: post
title: "Multi-Person Tracking by Multicut and Deep Matching"
date: 2016-08-17 13:53:13
categories: arXiv_CV
tags: arXiv_CV Tracking Optimization Detection
author: Siyu Tang, Bjoern Andres, Mykhaylo Andriluka, Bernt Schiele
mathjax: true
---

* content
{:toc}

##### Abstract
In [1], we proposed a graph-based formulation that links and clusters person hypotheses over time by solving a minimum cost subgraph multicut problem. In this paper, we modify and extend [1] in three ways: 1) We introduce a novel local pairwise feature based on local appearance matching that is robust to partial occlusion and camera motion. 2) We perform extensive experiments to compare different pairwise potentials and to analyze the robustness of the tracking formulation. 3) We consider a plain multicut problem and remove outlying clusters from its solution. This allows us to employ an efficient primal feasible optimization algorithm that is not applicable to the subgraph multicut problem of [1]. Unlike the branch-and-cut algorithm used there, this efficient algorithm used here is applicable to long videos and many detections. Together with the novel feature, it eliminates the need for the intermediate tracklet representation of [1]. We demonstrate the effectiveness of our overall approach on the MOT16 benchmark [2], achieving state-of-art performance.

##### Abstract (translated by Google)
在文献[1]中，我们提出了一个基于图的公式，通过求解一个最小代价子图multicut问题来连接和聚类人的假设。在本文中，我们通过三种方式对[1]进行修改和扩展：1）基于局部外观匹配，引入了局部闭合和相机运动稳健的新的局部配对特征。 2）我们进行大量的实验来比较不同的成对电位，并分析跟踪公式的鲁棒性。 3）我们考虑一个简单的multicut问题，并从其解决方案中删除外围集群。这使得我们可以采用一种有效的原始可行的优化算法，它不适用于[1]的子图多重分类问题。与那里使用的分支和剪切算法不同，这里使用的这种高效的算法适用于长视频和许多检测。与新颖的功能一起，它消除了[1]的中间轨迹表示的需要。我们在MOT16基准测试中证明了我们整体方法的有效性[2]，实现了最先进的性能。

##### URL
[https://arxiv.org/abs/1608.05404](https://arxiv.org/abs/1608.05404)

##### PDF
[https://arxiv.org/pdf/1608.05404](https://arxiv.org/pdf/1608.05404)

