---
layout: post
title: "Real-time Lane Marker Detection Using Template Matching with RGB-D Camera"
date: 2018-06-05 12:03:18
categories: arXiv_CV
tags: arXiv_CV Face Detection
author: Cong Hoang Quach, Van Lien Tran, Duy Hung Nguyen, Viet Thang Nguyen, Minh Trien Pham, Manh Duong Phung
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the problem of lane detection which is fundamental for self-driving vehicles. Our approach exploits both colour and depth information recorded by a single RGB-D camera to better deal with negative factors such as lighting conditions and lane-like objects. In the approach, colour and depth images are first converted to a half-binary format and a 2D matrix of 3D points. They are then used as the inputs of template matching and geometric feature extraction processes to form a response map so that its values represent the probability of pixels being lane markers. To further improve the results, the template and lane surfaces are finally refined by principal component analysis and lane model fitting techniques. A number of experiments have been conducted on both synthetic and real datasets. The result shows that the proposed approach can effectively eliminate unwanted noise to accurately detect lane markers in various scenarios. Moreover, the processing speed of 20 frames per second under hardware configuration of a popular laptop computer allows the proposed algorithm to be implemented for real-time autonomous driving applications.

##### Abstract (translated by Google)
本文论述了自动驾驶车辆的基本车道检测问题。我们的方法利用单个RGB-D摄像机记录的颜色和深度信息，以更好地处理照明条件和车道状物体等不利因素。在该方法中，颜色和深度图像首先被转换成半二进制格式和3D点的2D矩阵。然后将它们用作模板匹配和几何特征提取过程的输入，以形成响应图，以便其值表示像素成为车道标记的概率。为了进一步改善结果，模板和车道表面最终通过主成分分析和车道模型拟合技术来完善。已经对合成和真实数据集进行了大量实验。结果表明，所提出的方法可以有效地消除不必要的噪声，以在各种情况下准确检测车道标记。而且，在流行的膝上型计算机的硬件配置下每秒20帧的处理速度允许所提出的算法被实现用于实时自动驾驶应用。

##### URL
[http://arxiv.org/abs/1806.01621](http://arxiv.org/abs/1806.01621)

##### PDF
[http://arxiv.org/pdf/1806.01621](http://arxiv.org/pdf/1806.01621)

