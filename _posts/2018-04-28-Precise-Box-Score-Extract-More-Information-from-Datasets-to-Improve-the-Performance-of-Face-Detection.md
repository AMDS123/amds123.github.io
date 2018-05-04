---
layout: post
title: "Precise Box Score: Extract More Information from Datasets to Improve the Performance of Face Detection"
date: 2018-04-28 05:11:19
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face Detection Face_Detection
author: Ce Qi, Xiaoping Chen, Pingyu Wang, Fei Su
mathjax: true
---

* content
{:toc}

##### Abstract
For the training of face detection network based on R-CNN framework, anchors are assigned to be positive samples if intersection-over-unions (IoUs) with ground-truth are higher than the first threshold(such as 0.7); and to be negative samples if their IoUs are lower than the second threshold(such as 0.3). And the face detection model is trained by the above labels. However, anchors with IoU between first threshold and second threshold are not used. We propose a novel training strategy, Precise Box Score(PBS), to train object detection models. The proposed training strategy uses the anchors with IoUs between the first and second threshold, which can consistently improve the performance of face detection. Our proposed training strategy extracts more information from datasets, making better utilization of existing datasets. What's more, we also introduce a simple but effective model compression method(SEMCM), which can boost the performance of face detectors further. Experimental results show that the performance of face detection network can consistently be improved based on our proposed scheme.

##### Abstract (translated by Google)
对于基于R-CNN框架的人脸检测网络的训练，如果与地面真值相交的联合（IoUs）高于第一阈值（例如0.7），则将锚定分配为正样本;并且如果它们的IoU低于第二阈值（例如0.3）则为负样本。并且人脸检测模型由上述标签训练。但是，不使用IoU在第一阈值和第二阈值之间的锚。我们提出了一种新的培训策略，精确盒子评分（PBS），来训练对象检测模型。所提出的训练策略使用具有介于第一和第二阈值之间的IoU的锚点，其可以一致地改善人脸检测的性能。我们提出的培训策略从数据集中提取更多信息，更好地利用现有数据集。此外，我们还介绍了一种简单而有效的模型压缩方法（SEMCM），它可以进一步提高面部检测器的性能。实验结果表明，基于我们提出的方案，人脸检测网络的性能可以持续改善。

##### URL
[https://arxiv.org/abs/1804.10743](https://arxiv.org/abs/1804.10743)

##### PDF
[https://arxiv.org/pdf/1804.10743](https://arxiv.org/pdf/1804.10743)

