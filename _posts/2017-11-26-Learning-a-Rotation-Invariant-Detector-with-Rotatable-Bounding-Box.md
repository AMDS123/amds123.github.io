---
layout: post
title: "Learning a Rotation Invariant Detector with Rotatable Bounding Box"
date: 2017-11-26 15:20:52
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Lei Liu, Zongxu Pan, Bin Lei
mathjax: true
---

* content
{:toc}

##### Abstract
Detection of arbitrarily rotated objects is a challenging task due to the difficulties of locating the multi-angle objects and separating them effectively from the background. The existing methods are not robust to angle varies of the objects because of the use of traditional bounding box, which is a rotation variant structure for locating rotated objects. In this article, a new detection method is proposed which applies the newly defined rotatable bounding box (RBox). The proposed detector (DRBox) can effectively handle the situation where the orientation angles of the objects are arbitrary. The training of DRBox forces the detection networks to learn the correct orientation angle of the objects, so that the rotation invariant property can be achieved. DRBox is tested to detect vehicles, ships and airplanes on satellite images, compared with Faster R-CNN and SSD, which are chosen as the benchmark of the traditional bounding box based methods. The results shows that DRBox performs much better than traditional bounding box based methods do on the given tasks, and is more robust against rotation of input image and target objects. Besides, results show that DRBox correctly outputs the orientation angles of the objects, which is very useful for locating multi-angle objects efficiently. The code and models are available at this https URL

##### Abstract (translated by Google)
任意旋转物体的检测是一个具有挑战性的任务，因为定位多角度物体和将其有效地从背景分离是困难的。现有方法由于使用了传统的边界框，这是一种用于定位旋转对象的旋转变体结构，因此对角度变化的对象不够鲁棒。在这篇文章中，提出了一种新的检测方法，应用了新定义的旋转包围盒（RBox）。所提出的检测器（DRBox）能够有效地处理物体的方位角是任意的情况。 DRBox的训练迫使检测网络学习物体的正确方位角，从而实现旋转不变性。 DRBox经过测试，可以在卫星图像上检测车辆，船舶和飞机，而R-CNN和SSD则是以传统的基于边界框的方法为基准。结果表明DRBox比传统的基于边界框的方法在给定的任务上执行得更好，并且对于输入图像和目标对象的旋转更加鲁棒。此外，结果表明，DRBox能正确输出对象的方位角，这对于高效定位多角度对象非常有用。代码和模型可在此https URL中找到

##### URL
[https://arxiv.org/abs/1711.09405](https://arxiv.org/abs/1711.09405)

##### PDF
[https://arxiv.org/pdf/1711.09405](https://arxiv.org/pdf/1711.09405)

