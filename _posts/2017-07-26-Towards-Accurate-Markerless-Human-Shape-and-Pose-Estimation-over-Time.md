---
layout: post
title: "Towards Accurate Markerless Human Shape and Pose Estimation over Time"
date: 2017-07-26 19:28:39
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation
author: Yinghao Huang, Federica Bogo, Christoph Classner, Angjoo Kanazawa, Peter V. Gehler, Ijaz Akhter, Michael J. Black
mathjax: true
---

* content
{:toc}

##### Abstract
Existing marker-less motion capture methods often assume known backgrounds, static cameras, and sequence specific motion priors, which narrows its application scenarios. Here we propose a fully automatic method that given multi-view video, estimates 3D human motion and body shape. We take recent SMPLify \cite{bogo2016keep} as the base method, and extend it in several ways. First we fit the body to 2D features detected in multi-view images. Second, we use a CNN method to segment the person in each image and fit the 3D body model to the contours to further improves accuracy. Third we utilize a generic and robust DCT temporal prior to handle the left and right side swapping issue sometimes introduced by the 2D pose estimator. Validation on standard benchmarks shows our results are comparable to the state of the art and also provide a realistic 3D shape avatar. We also demonstrate accurate results on HumanEva and on challenging dance sequences from YouTube in monocular case.

##### Abstract (translated by Google)
现有的无标记运动捕捉方法通常假定已知背景，静态相机和序列特定的运动先验，这缩小了其应用场景。在这里，我们提出了一个全自动的方法，给多视角视频，估计3D人体运动和身体形状。我们以最近的SMPLify \ cite {bogo2016keep}为基础方法，并以几种方式扩展它。首先，我们将身体适合于在多视图图像中检测到的2D特征。其次，我们使用CNN方法对每个图像中的人物进行分割，并将三维人体模型拟合到轮廓上，以进一步提高准确性。第三，我们在处理由2D姿态估计器有时引入的左侧和右侧交换问题之前，使用通用和强健的DCT时间。标准基准的验证表明我们的结果与现有技术水平相当，并提供了逼真的3D形状化身。我们还在单眼情况下展示了HumanEva的精确结果以及来自YouTube的具有挑战性的舞蹈序列。

##### URL
[https://arxiv.org/abs/1707.07548](https://arxiv.org/abs/1707.07548)

##### PDF
[https://arxiv.org/e-print/1707.07548](https://arxiv.org/e-print/1707.07548)

