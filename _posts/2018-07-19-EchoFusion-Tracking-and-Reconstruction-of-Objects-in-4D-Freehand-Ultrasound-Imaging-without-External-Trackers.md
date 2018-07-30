---
layout: post
title: "EchoFusion: Tracking and Reconstruction of Objects in 4D Freehand Ultrasound Imaging without External Trackers"
date: 2018-07-19 12:07:50
categories: arXiv_CV
tags: arXiv_CV Segmentation Tracking Deep_Learning Quantitative SLAM
author: Bishesh Khanal, Alberto Gomez, Nicolas Toussaint, Steven McDonagh, Veronika Zimmer, Emily Skelton, Jacqueline Matthew, Daniel Grzech, Robert Wright, Chandni Gupta, Benjamin Hou, Daniel Rueckert, Julia A.Schnabel, Bernhard Kainz
mathjax: true
---

* content
{:toc}

##### Abstract
Ultrasound (US) is the most widely used fetal imaging technique. However, US images have limited capture range, and suffer from view dependent artefacts such as acoustic shadows. Compounding of overlapping 3D US acquisitions into a high-resolution volume can extend the field of view and remove image artefacts, which is useful for retrospective analysis including population based studies. However, such volume reconstructions require information about relative transformations between probe positions from which the individual volumes were acquired. In prenatal US scans, the fetus can move independently from the mother, making external trackers such as electromagnetic or optical tracking unable to track the motion between probe position and the moving fetus. We provide a novel methodology for image-based tracking and volume reconstruction by combining recent advances in deep learning and simultaneous localisation and mapping (SLAM). Tracking semantics are established through the use of a Residual 3D U-Net and the output is fed to the SLAM algorithm. As a proof of concept, experiments are conducted on US volumes taken from a whole body fetal phantom, and from the heads of real fetuses. For the fetal head segmentation, we also introduce a novel weak annotation approach to minimise the required manual effort for ground truth annotation. We evaluate our method qualitatively, and quantitatively with respect to tissue discrimination accuracy and tracking robustness.

##### Abstract (translated by Google)
超声（US）是最广泛使用的胎儿成像技术。然而，US图像具有有限的捕获范围，并且受到视觉依赖性伪像（例如声学阴影）的影响。将重叠的3D US采集复合到高分辨率体积中可以扩展视野并去除图像伪像，这对于包括基于群体的研究的回顾性分析是有用的。然而，这样的体积重建需要关于从中获取各个体积的探针位置之间的相对变换的信息。在产前美国扫描中，胎儿可以独立于母亲移动，使得诸如电磁或光学跟踪的外部跟踪器不能跟踪探头位置和移动胎儿之间的运动。我们结合深度学习和同步定位与映射（SLAM）的最新进展，为基于图像的跟踪和体积重建提供了一种新颖的方法。通过使用残余3D U-Net建立跟踪语义，并将输出馈送到SLAM算法。作为概念证明，对从美体胎儿体模和真实胎儿头部取得的美国体积进行实验。对于胎儿头部分割，我们还引入了一种新颖的弱注释方法，以最小化地面实况注释所需的手动努力。我们定性评估我们的方法，并定量评估组织辨别准确性和跟踪稳健性。

##### URL
[http://arxiv.org/abs/1807.10583](http://arxiv.org/abs/1807.10583)

##### PDF
[http://arxiv.org/pdf/1807.10583](http://arxiv.org/pdf/1807.10583)

