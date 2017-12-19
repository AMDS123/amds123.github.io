---
layout: post
title: "Depth Extraction from Videos Using Geometric Context and Occlusion Boundaries"
date: 2015-10-25 22:41:24
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Relation
author: S. Hussain Raza, Omar Javed, Aveek Das, Harpreet Sawhney, Hui Cheng, Irfan Essa
mathjax: true
---

* content
{:toc}

##### Abstract
We present an algorithm to estimate depth in dynamic video scenes. We propose to learn and infer depth in videos from appearance, motion, occlusion boundaries, and geometric context of the scene. Using our method, depth can be estimated from unconstrained videos with no requirement of camera pose estimation, and with significant background/foreground motions. We start by decomposing a video into spatio-temporal regions. For each spatio-temporal region, we learn the relationship of depth to visual appearance, motion, and geometric classes. Then we infer the depth information of new scenes using piecewise planar parametrization estimated within a Markov random field (MRF) framework by combining appearance to depth learned mappings and occlusion boundary guided smoothness constraints. Subsequently, we perform temporal smoothing to obtain temporally consistent depth maps. To evaluate our depth estimation algorithm, we provide a novel dataset with ground truth depth for outdoor video scenes. We present a thorough evaluation of our algorithm on our new dataset and the publicly available Make3d static image dataset.

##### Abstract (translated by Google)
我们提出一个算法来估计动态视频场景的深度。我们建议从外观，运动，遮挡边界和场景的几何背景中学习和推断视频的深度。使用我们的方法，可以从无约束视频估计深度，而不需要相机姿态估计，并具有显着的背景/前景运动。我们首先将视频分解为时空区域。对于每个时空区域，我们学习深度与视觉外观，运动和几何类的关系。然后通过将外观与深度学习映射和遮挡边界引导平滑约束相结合，使用在马尔可夫随机场（MRF）框架内估计的分段平面参数化来推断新场景的深度信息。随后，我们进行时间平滑，以获得时间一致的深度图。为了评估我们的深度估计算法，我们为户外视频场景提供了一个具有地面真实深度的新数据集。我们在我们的新数据集和公开可用的Make3d静态图像数据集上提出了对我们算法的全面评估。

##### URL
[https://arxiv.org/abs/1510.07317](https://arxiv.org/abs/1510.07317)

##### PDF
[https://arxiv.org/pdf/1510.07317](https://arxiv.org/pdf/1510.07317)

