---
layout: post
title: "A graph cut approach to 3D tree delineation, using integrated airborne LiDAR and hyperspectral imagery"
date: 2017-01-24 02:41:30
categories: arXiv_CV
tags: arXiv_CV Detection
author: Juheon Lee, David Coomes, Carola-Bibiane Schonlieb, Xiaohao Cai, Jan Lellmann, Michele Dalponte, Yadvinder Malhi, Nathalie Butt, Mike Morecroft
mathjax: true
---

* content
{:toc}

##### Abstract
Recognising individual trees within remotely sensed imagery has important applications in forest ecology and management. Several algorithms for tree delineation have been suggested, mostly based on locating local maxima or inverted basins in raster canopy height models (CHMs) derived from Light Detection And Ranging (LiDAR) data or photographs. However, these algorithms often lead to inaccurate estimates of forest stand characteristics due to the limited information content of raster CHMs. Here we develop a 3D tree delineation method which uses graph cut to delineate trees from the full 3D LiDAR point cloud, and also makes use of any optical imagery available (hyperspectral imagery in our case). First, conventional methods are used to locate local maxima in the CHM and generate an initial map of trees. Second, a graph is built from the LiDAR point cloud, fused with the hyperspectral data. For computational efficiency, the feature space of hyperspectral imagery is reduced using robust PCA. Third, a multi-class normalised cut is applied to the graph, using the initial map of trees to constrain the number of clusters and their locations. Finally, recursive normalised cut is used to subdivide, if necessary, each of the clusters identified by the initial analysis. We call this approach Multiclass Cut followed by Recursive Cut (MCRC). The effectiveness of MCRC was tested using three datasets: i) NewFor, ii) a coniferous forest in the Italian Alps, and iii) a deciduous woodland in the UK. The performance of MCRC was usually superior to that of other delineation methods, and was further improved by including high-resolution optical imagery. Since MCRC delineates the entire LiDAR point cloud in 3D, it allows individual crown characteristics to be measured. By making full use of the data available, graph cut has the potential to considerably improve the accuracy of tree delineation.

##### Abstract (translated by Google)
识别遥感影像中的单个树木在森林生态学和管理中具有重要的应用。已经提出了几种用于树状划分的算法，主要基于从光检测和测距（LiDAR）数据或照片导出的光栅冠层高度模型（CHM）中定位局部最大值或倒置盆地。然而，由于栅格中间件的信息量有限，这些算法通常会导致对林分特征的估计不准确。在这里，我们开发了一种三维树状划分方法，该方法使用图形切割来从完整的三维LiDAR点云中描绘树木，并利用任何可用的光学图像（本例中为高光谱图像）。首先，使用常规方法来定位CHM中的局部最大值并生成树的初始图。其次，利用LiDAR点云建立图谱，与高光谱数据融合。为了计算效率，使用稳健的PCA来降低高光谱图像的特征空间。第三，使用树的初始映射来限制簇的数目及其位置，对该图应用多类归一化剪切。最后，递归归一化切割被用于细分（如果需要的话）由初始分析所识别的每个集群。我们把这种方法称为多重切割，然后是递归切割（MCRC）。 MCRC的有效性使用三个数据集进行测试：i）NewFor，ii）意大利阿尔卑斯山的针叶林，以及iii）英国的落叶林地。 MCRC的性能通常优于其他描述方法，并且通过包含高分辨率光学图像进一步改善。由于MCRC以3D形式描绘整个LiDAR点云，因此可以测量个别冠部特征。通过充分利用可用的数据，图形切割有可能显着提高树划定的准确性。

##### URL
[https://arxiv.org/abs/1701.06715](https://arxiv.org/abs/1701.06715)

##### PDF
[https://arxiv.org/pdf/1701.06715](https://arxiv.org/pdf/1701.06715)

