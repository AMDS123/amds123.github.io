---
layout: post
title: "Efficient two step optimization for large embedded deformation graph based SLAM"
date: 2019-06-20 07:36:16
categories: arXiv_CV
tags: arXiv_CV Optimization SLAM
author: Jingwei Song, Fang Bai, Liang Zhao, Shoudong Huang, Rong Xiong
mathjax: true
---

* content
{:toc}

##### Abstract
Embedded deformation nodes based formulation has been widely applied in deformable geometry and graphical problems. Though being promising in stereo (or RGBD) sensor based SLAM applications, it remains challenging to keep constant speed in deformation nodes parameter estimation when model grows larger. In practice, the processing time grows rapidly in accordance with the expansion of maps. In this paper, we propose an approach to decouple nodes of deformation graph in large scale dense deformable SLAM and keep the estimation time to be constant. We observe that only partial deformable nodes in the graph are connected to visible points. Based on this fact, sparsity of original Hessian matrix is utilized to split parameter estimation in two independent steps. With this new technique, we achieve faster parameter estimation with amortized computation complexity reduced from O(n^2) to closing O(1). As a result, the computation cost barely increases as the map keeps growing. Based on our strategy, computational bottleneck in large scale embedded deformation graph based applications will be greatly mitigated. The effectiveness is validated by experiments, featuring large scale deformation scenarios.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.08477](http://arxiv.org/abs/1906.08477)

##### PDF
[http://arxiv.org/pdf/1906.08477](http://arxiv.org/pdf/1906.08477)

