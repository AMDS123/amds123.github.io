---
layout: post
title: "X-ray-transform Invariant Anatomical Landmark Detection for Pelvic Trauma Surgery"
date: 2018-03-22 23:09:50
categories: arXiv_CV
tags: arXiv_CV Knowledge Pose_Estimation CNN Prediction Detection
author: Bastian Bier, Mathias Unberath, Jan-Nico Zaech, Javad Fotouhi, Mehran Armand, Greg Osgood, Nassir Navab, Andreas Maier
mathjax: true
---

* content
{:toc}

##### Abstract
X-ray image guidance enables percutaneous alternatives to complex procedures. Unfortunately, the indirect view onto the anatomy in addition to projective simplification substantially increase the task-load for the surgeon. Additional 3D information such as knowledge of anatomical landmarks can benefit surgical decision making in complicated scenarios. Automatic detection of these landmarks in transmission imaging is challenging since image-domain features characteristic to a certain landmark change substantially depending on the viewing direction. Consequently and to the best of our knowledge, the above problem has not yet been addressed. In this work, we present a method to automatically detect anatomical landmarks in X-ray images independent of the viewing direction. To this end, a sequential prediction framework based on convolutional layers is trained on synthetically generated data of the pelvic anatomy to predict 23 landmarks in single X-ray images. View independence is contingent on training conditions and, here, is achieved on a spherical segment covering (120 x 90) degrees in LAO/RAO and CRAN/CAUD, respectively, centered around AP. On synthetic data, the proposed approach achieves a mean prediction error of 5.6 +- 4.5 mm. We demonstrate that the proposed network is immediately applicable to clinically acquired data of the pelvis. In particular, we show that our intra-operative landmark detection together with pre-operative CT enables X-ray pose estimation which, ultimately, benefits initialization of image-based 2D/3D registration.

##### Abstract (translated by Google)
X射线图像引导使复杂程序的经皮替代成为可能。不幸的是，除了投影简化之外，对解剖结构的间接观察大大增加了外科医生的任务负担。额外的3D信息，如解剖标志的知识，可以在复杂的情况下有利于手术决策。传输成像中这些界标的自动检测是具有挑战性的，因为特定界标的图像域特征基本上取决于观察方向而改变。因此，就我们所知，上述问题尚未得到解决。在这项工作中，我们提出了一种自动检测与观察方向无关的X射线图像中的解剖标志的方法。为此，基于卷积层的顺序预测框架通过合成生成的骨盆解剖数据进行训练，以预测单个X射线图像中的23个地标。观看独立性取决于训练条件，并且在LAO / RAO和CRAN / CAUD中分别以AP为中心覆盖（120 x 90）度的球形片段实现。在合成数据上，所提出的方法实现5.6±4.5mm的平均预测误差。我们证明拟议的网络立即适用于骨盆临床获得的数据。特别是，我们显示我们的术中标志物检测与手术前CT一起使X射线姿态估计成为可能，最终有利于基于图像的2D / 3D配准的初始化。

##### URL
[https://arxiv.org/abs/1803.08608](https://arxiv.org/abs/1803.08608)

##### PDF
[https://arxiv.org/pdf/1803.08608](https://arxiv.org/pdf/1803.08608)

