---
layout: post
title: "Learning Monocular 3D Human Pose Estimation from Multi-view Images"
date: 2018-03-13 13:14:47
categories: arXiv_CV
tags: arXiv_CV Regularization Pose_Estimation Prediction
author: Helge Rhodin, J&#xf6;rg Sp&#xf6;rri, Isinsu Katircioglu, Victor Constantin, Fr&#xe9;d&#xe9;ric Meyer, Erich M&#xfc;ller, Mathieu Salzmann, Pascal Fua
mathjax: true
---

* content
{:toc}

##### Abstract
Accurate 3D human pose estimation from single images is possible with sophisticated deep-net architectures that have been trained on very large datasets. However, this still leaves open the problem of capturing motions for which no such database exists. Manual annotation is tedious, slow, and error-prone. In this paper, we propose to replace most of the annotations by the use of multiple views, at training time only. Specifically, we train the system to predict the same pose in all views. Such a consistency constraint is necessary but not sufficient to predict accurate poses. We therefore complement it with a supervised loss aiming to predict the correct pose in a small set of labeled images, and with a regularization term that penalizes drift from initial predictions. Furthermore, we propose a method to estimate camera pose jointly with human pose, which lets us utilize multi-view footage where calibration is difficult, e.g., for pan-tilt or moving handheld cameras. We demonstrate the effectiveness of our approach on established benchmarks, as well as on a new Ski dataset with rotating cameras and expert ski motion, for which annotations are truly hard to obtain.

##### Abstract (translated by Google)
精密的三维人体姿势估计可以通过精密的深度网络架构进行训练，这些架构已经在非常大的数据集上进行了训练。但是，这仍然会导致捕获没有这种数据库存在的运动的问题。手动注释非常繁琐，速度慢且容易出错。在本文中，我们建议仅在培训时使用多个视图来替换大多数注释。具体来说，我们训练系统预测所有视图中的相同姿势。这种一致性约束是必要的，但不足以预测准确的姿势。因此，我们用一个监督损失来补充它，目的是预测一小组标记图像中的正确姿势，并用正则化术语来惩罚初始预测中的漂移。此外，我们提出了一种与人体姿势一起估计相机姿态的方法，其允许我们利用多视图素材在难以校准的情况下，例如用于平移或移动手持相机。我们展示了我们的方法在建立的基准测试中的有效性，以及带有旋转摄像头和专业滑雪运动的新的Ski数据集，这些数据真正难以获得注释。

##### URL
[http://arxiv.org/abs/1803.04775](http://arxiv.org/abs/1803.04775)

##### PDF
[http://arxiv.org/pdf/1803.04775](http://arxiv.org/pdf/1803.04775)

