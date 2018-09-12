---
layout: post
title: "Hubless keypoint-based 3D deformable groupwise registration"
date: 2018-09-11 14:59:03
categories: arXiv_CV
tags: arXiv_CV Segmentation Optimization Detection Gradient_Descent
author: R&#xe9;mi Agier, S&#xe9;bastien Valette, Razmig K&#xe9;chichian, Laurent Fanton, R&#xe9;my Prost
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel deformable groupwise registration method, applied to large 3D image groups. Our approach extracts 3D SURF keypoints from images, computes matched pairs of keypoints and registers the group by minimizing pair distances in a hubless way i.e. without computing any central mean image. Using keypoints significantly reduces the problem complexity compared to voxel-based approaches, and enables us to provide an in-core global optimization, similar to the Bundle Adjustment for 3D reconstruction. As we aim at registering images of different patients, the matching step yields many outliers. Then we propose a new EM-weighting algorithm which efficiently discards outliers. Global optimization is carried out with a fast gradient descent algorithm. This allows our approach to robustly register large datasets. The result is a set of half transforms which link the volumes together and can be subsequently exploited for computational anatomy, landmark detection or image segmentation. We show experimental results on whole-body CT scans, with groups of up to 103 volumes. On a benchmark based on anatomical landmarks, our algorithm compares favorably with the star-groupwise voxel-based ANTs and NiftyReg approaches while being much faster. We also discuss the limitations of our approach for lower resolution images such as brain MRI.

##### Abstract (translated by Google)
我们提出了一种新的可变形分组配准方法，适用于大型3D图像组。我们的方法从图像中提取3D SURF关键点，计算匹配的关键点对并通过以无人方式最小化对距离来登记该组，即不计算任何中心平均图像。与基于体素的方法相比，使用关键点可显着降低问题复杂性，并使我们能够提供内核全局优化，类似于3D重建的捆绑调整。由于我们的目标是记录不同患者的图像，因此匹配步骤会产生许多异常值。然后我们提出了一种新的EM加权算法，可以有效地丢弃异常值。使用快速梯度下降算法执行全局优化。这允许我们的方法可以稳健地注册大型数据集。结果是一组半变换，其将体积链接在一起并且随后可以用于计算解剖，界标检测或图像分割。我们展示了全身CT扫描的实验结果，最多可达103个体积。在基于解剖标志的基准测试中，我们的算法与基于星组的基于体素的ANT和NiftyReg方法相比更有利，同时速度更快。我们还讨论了我们的方法对于低分辨率图像（如脑MRI）的局限性。

##### URL
[http://arxiv.org/abs/1809.03951](http://arxiv.org/abs/1809.03951)

##### PDF
[http://arxiv.org/pdf/1809.03951](http://arxiv.org/pdf/1809.03951)

