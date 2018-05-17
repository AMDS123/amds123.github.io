---
layout: post
title: "Robust 6D Object Pose Estimation with Stochastic Congruent Sets"
date: 2018-05-16 13:43:00
categories: arXiv_CV
tags: arXiv_CV Segmentation Pose_Estimation Semantic_Segmentation Optimization
author: Chaitanya Mitash, Abdeslam Boularias, Kostas Bekris
mathjax: true
---

* content
{:toc}

##### Abstract
Object pose estimation is frequently achieved by first segmenting an RGB image and then, given depth data, registering the corresponding point cloud segment against the object's 3D model. Despite the progress due to CNNs, semantic segmentation output can be noisy, especially when the CNN is only trained on synthetic data. This causes registration methods to fail in estimating a good object pose. This work proposes a novel stochastic optimization process that treats the segmentation output of CNNs as a confidence probability. The algorithm, called Stochastic Congruent Sets (StoCS), samples pointsets on the point cloud according to the soft segmentation distribution and so as to agree with the object's known geometry. The pointsets are then matched to congruent sets on the 3D object model to generate pose estimates. StoCS is shown to be robust on an APC dataset, despite the fact the CNN is trained only on synthetic data. In the YCB dataset, StoCS outperforms a recent network for 6D pose estimation and alternative pointset matching techniques.

##### Abstract (translated by Google)
对象位姿估算常常通过首先对RGB图像进行分段，然后在给定深度数据的情况下将对应的点云段针对对象的3D模型进行配准来实现。尽管CNN取得了进展，但语义分割输出可能会很嘈杂，尤其是当CNN仅仅通过合成数据进行训练时。这会导致注册方法无法估计出良好的对象姿态。这项工作提出了一种新的随机优化过程，将CNN的分割输出视为置信概率。称为随机全等集（StoCS）的算法根据软分割分布对点云上的点集进行采样，以便与对象的已知几何形状一致。然后将点集与3D对象模型上的全等集相匹配以生成姿态估计。尽管CNN仅在合成数据上进行了训练，但StoCS在APC数据集上表现出很强大。在YCB数据集中，StoCS优于最近的6D姿态估计网络和替代点集匹配技术。

##### URL
[http://arxiv.org/abs/1805.06324](http://arxiv.org/abs/1805.06324)

##### PDF
[http://arxiv.org/pdf/1805.06324](http://arxiv.org/pdf/1805.06324)

