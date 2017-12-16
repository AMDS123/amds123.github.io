---
layout: post
title: "A Fully Convolutional Network for Semantic Labeling of 3D Point Clouds"
date: 2017-10-03 22:35:25
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Detection
author: Mohammed Yousefhussien, David J. Kelbe, Emmett J. Ientilucci, Carl Salvaggio
mathjax: true
---

* content
{:toc}

##### Abstract
When classifying point clouds, a large amount of time is devoted to the process of engineering a reliable set of features which are then passed to a classifier of choice. Generally, such features - usually derived from the 3D-covariance matrix - are computed using the surrounding neighborhood of points. While these features capture local information, the process is usually time-consuming, and requires the application at multiple scales combined with contextual methods in order to adequately describe the diversity of objects within a scene. In this paper we present a 1D-fully convolutional network that consumes terrain-normalized points directly with the corresponding spectral data,if available, to generate point-wise labeling while implicitly learning contextual features in an end-to-end fashion. Our method uses only the 3D-coordinates and three corresponding spectral features for each point. Spectral features may either be extracted from 2D-georeferenced images, as shown here for Light Detection and Ranging (LiDAR) point clouds, or extracted directly for passive-derived point clouds,i.e. from muliple-view imagery. We train our network by splitting the data into square regions, and use a pooling layer that respects the permutation-invariance of the input points. Evaluated using the ISPRS 3D Semantic Labeling Contest, our method scored second place with an overall accuracy of 81.6%. We ranked third place with a mean F1-score of 63.32%, surpassing the F1-score of the method with highest accuracy by 1.69%. In addition to labeling 3D-point clouds, we also show that our method can be easily extended to 2D-semantic segmentation tasks, with promising initial results.

##### Abstract (translated by Google)
在对点云进行分类时，需要大量的时间来处理一系列可靠的特征，然后将这些特征传递给选定的分类器。一般来说，这些特征（通常是从三维协方差矩阵导出的）是使用周围的点来计算的。虽然这些功能捕捉本地信息，但是这个过程通常是耗时的，并且需要将多个尺度的应用程序与上下文方法结合起来，以充分描述场景内物体的多样性。在本文中，我们提出一个完全卷积网络，如果可用的话，直接使用地形归一化的点来生成点标记，同时以端到端的方式隐式学习上下文特征。我们的方法只使用3D坐标和每个点的三个相应的光谱特征。光谱特征可以从二维地理参考图像中提取，如这里对于光检测和测距（LiDAR）点云所示，或者直接从被动衍生的点云中提取，从多视角图像。我们通过将数据分成正方形区域来训练我们的网络，并使用一个尊重输入点的置换不变性的共享层。使用ISPRS 3D语义标注竞赛进行评估，我们的方法获得了第二名，总体准确率为81.6％。我们以平均F1得分为63.32％排名第三，超过了方法的F1得分，最高的准确率为1.69％。除了标注3D点云，我们还表明，我们的方法可以很容易地扩展到二维语义分割任务，有前途的初步结果。

##### URL
[https://arxiv.org/abs/1710.01408](https://arxiv.org/abs/1710.01408)

##### PDF
[https://arxiv.org/pdf/1710.01408](https://arxiv.org/pdf/1710.01408)

