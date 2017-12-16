---
layout: post
title: "Identifying Most Walkable Direction for Navigation in an Outdoor Environment"
date: 2017-12-01 03:18:52
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation
author: Sachin Mehta, Hannaneh Hajishirzi, Linda Shapiro
mathjax: true
---

* content
{:toc}

##### Abstract
We present an approach for identifying the most walkable direction for navigation using a hand-held camera. Our approach extracts semantically rich contextual information from the scene using a custom encoder-decoder architecture for semantic segmentation and models the spatial and temporal behavior of objects in the scene using a spatio-temporal graph. The system learns to minimize a cost function over the spatial and temporal object attributes to identify the most walkable direction. We construct a new annotated navigation dataset collected using a hand-held mobile camera in an unconstrained outdoor environment, which includes challenging settings such as highly dynamic scenes, occlusion between objects, and distortions. Our system achieves an accuracy of 84% on predicting a safe direction. We also show that our custom segmentation network is both fast and accurate, achieving mIOU (mean intersection over union) scores of 81 and 44.7 on the PASCAL VOC and the PASCAL Context datasets, respectively, while running at about 21 frames per second.

##### Abstract (translated by Google)
我们提出了一种方法来确定使用手持摄像头进行导航的最适合步行的方向。我们的方法使用自定义的编码器 - 解码器体系结构从场景中抽取语义丰富的上下文信息进行语义分割，并使用时空图形对场景中对象的空间和时间行为进行建模。系统学习将空间和时间对象属性上的成本函数最小化以识别最可行的方向。我们构建了一个新的注释导航数据集收集使用手持移动相机在一个不受限制的室外环境，其中包括具有挑战性的设置，如高度动态的场景，对象之间的遮挡和扭曲。我们的系统在预测安全方向上达到了84％的准确率。我们还显示，我们的自定义分割网络既快速又准确，实现了分别在PASCAL VOC和PASCAL Context数据集上的81和44.7的mIOU（平均交叉联合）分数，而以约21帧/秒的速度运行。

##### URL
[https://arxiv.org/abs/1711.08040](https://arxiv.org/abs/1711.08040)

##### PDF
[https://arxiv.org/pdf/1711.08040](https://arxiv.org/pdf/1711.08040)

