---
layout: post
title: "EREL Selection using Morphological Relation"
date: 2018-06-10 04:03:46
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Detection Relation
author: Yuying Li, Mehdi Faraji
mathjax: true
---

* content
{:toc}

##### Abstract
This work concentrates on Extremal Regions of Extremum Level (EREL) selection. EREL is a recently proposed feature detector aiming at detecting regions from a set of extremal regions. This is a branching problem derived from segmentation of arterial wall boundaries from Intravascular Ultrasound (IVUS) images. For each IVUS frame, a set of EREL regions is generated to describe the luminal area of human coronary. Each EREL is then fitted by an ellipse to represent the luminal border. The goal is to assign the most appropriate EREL as the lumen. In this work, EREL selection carries out in two rounds. In the first round, the pattern in a set of EREL regions is analyzed and used to generate an approximate luminal region. Then, the two-dimensional (2D) correlation coefficients are computed between this approximate region and each EREL to keep the ones with tightest relevance. In the second round, a compactness measure is calculated for each EREL and its fitted ellipse to guarantee that the resulting EREL has not affected by the common artifacts such as bifurcations, shadows, and side branches. We evaluated the selected ERELs in terms of Hausdorff Distance (HD) and Jaccard Measure (JM) on the train and test set of a publicly available dataset. The results show that our selection strategy outperforms the current state-of-the-art.

##### Abstract (translated by Google)
这项工作集中在极值极限水平（EREL）选择。 EREL是最近提出的特征检测器，旨在检测来自一组极值区域的区域。这是从血管内超声（IVUS）图像分割动脉壁边界得出的分支问题。对于每个IVUS帧，生成一组EREL区域来描述人体冠状动脉的腔区域。然后每个EREL用椭圆拟合以表示腔的边界。目标是将最合适的EREL指定为流明。在这项工作中，EREL选择分两轮进行。在第一轮中，对一组EREL区域中的模式进行分析并用于生成近似的鲁米那区域。然后，在该近似区域和每个EREL之间计算二维（2D）相关系数以保持具有最紧密相关性的相关系数。在第二轮中，计算每个EREL及其拟合椭圆的紧致度量，以保证所得到的EREL不受诸如分叉，阴影和侧分支的常见伪影的影响。我们根据列车上的Hausdorff距离（HD）和Jaccard测量（JM）和公开可用数据集的测试集评估选定的EREL。结果表明，我们的选择策略胜过了当前最先进的技术。

##### URL
[http://arxiv.org/abs/1806.03580](http://arxiv.org/abs/1806.03580)

##### PDF
[http://arxiv.org/pdf/1806.03580](http://arxiv.org/pdf/1806.03580)

