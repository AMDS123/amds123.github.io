---
layout: post
title: "Abnormal Event Detection and Location for Dense Crowds using Repulsive Forces and Sparse Reconstruction"
date: 2018-08-21 03:24:00
categories: arXiv_CV
tags: arXiv_CV Sparse Tracking Detection
author: Pei Lv, Shunhua Liu, Mingliang Xu, Bing Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a method based on repulsive forces and sparse reconstruction for the detection and location of abnormal events in crowded scenes. In order to avoid the challenging problem of accurately tracking each specific individual in a dense or complex scene, we divide each frame of the surveillance video into a fixed number of grids and select a single representative point in each grid as the individual to track. The repulsive force model, which can accurately reflect interactive behaviors of crowds, is used to calculate the interactive forces between grid particles in crowded scenes and to construct a force flow matrix using these discrete forces from a fixed number of continuous frames. The force flow matrix, which contains spatial and temporal information, is adopted to train a group of visual dictionaries by sparse coding. To further improve the detection efficiency and avoid concept drift, we propose a fully unsupervised global and local dynamic updating algorithm, based on sparse reconstruction and a group of word pools. For anomaly location, since our method is based on a fixed grid, we can judge whether anomalies occur in a region intuitively according to the reconstruction error of the corresponding visual words. We experimentally verify the proposed method using the UMN dataset, the UCSD dataset and the Web dataset separately. The results indicate that our method can not only detect abnormal events accurately, but can also pinpoint the location of anomalies.

##### Abstract (translated by Google)
本文提出了一种基于排斥力和稀疏重建的方法，用于拥挤场景中异常事件的检测和定位。为了避免在密集或复杂场景中精确跟踪每个特定个体的挑战性问题，我们将监视视频的每个帧划分为固定数量的网格，并选择每个网格中的单个代表点作为要跟踪的个体。排斥力模型可以准确地反映人群的交互行为，用于计算拥挤场景中网格粒子之间的相互作用力，并使用来自固定数量的连续帧的这些离散力构建力流矩阵。包含空间和时间信息的力流矩阵被用于通过稀疏编码训练一组视觉词典。为了进一步提高检测效率并避免概念漂移，我们提出了一种基于稀疏重构和一组字池的完全无监督的全局和局部动态更新算法。对于异常定位，由于我们的方法基于固定网格，我们可以根据相应视觉词的重建误差直观地判断区域中是否出现异常。我们分别使用UMN数据集，UCSD数据集和Web数据集实验验证了所提出的方法。结果表明，我们的方法不仅可以准确地检测异常事件，还可以查明异常的位置。

##### URL
[http://arxiv.org/abs/1808.06749](http://arxiv.org/abs/1808.06749)

##### PDF
[http://arxiv.org/pdf/1808.06749](http://arxiv.org/pdf/1808.06749)

