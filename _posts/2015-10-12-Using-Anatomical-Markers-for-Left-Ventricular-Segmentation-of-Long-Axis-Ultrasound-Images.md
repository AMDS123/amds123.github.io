---
layout: post
title: "Using Anatomical Markers for Left Ventricular Segmentation of Long Axis Ultrasound Images"
date: 2015-10-12 12:20:23
categories: arXiv_CV
tags: arXiv_CV Segmentation Detection
author: Yael Petrank, Nahum Smirin, Yossi Tsadok, Zvi Friedman, Peter Lysiansky, Dan Adam
mathjax: true
---

* content
{:toc}

##### Abstract
Left ventricular segmentation is essential for measuring left ventricular function indices. Segmentation of one or several images requires an initial guess of the contour. It is hypothesized here that creating an initial guess by first detecting anatomical markers, would lead to correct detection of the endocardium. The first step of the algorithm presented here includes automatic detection of the mitral valve. Next, the apex is detected in the same frame. The valve is then tracked throughout the cardiac cycle. Contours passing from the apex to each valve corner are then found using a dynamic programming algorithm. The resulting contour is used as an input to an active contour algorithm. The algorithm was tested on 21 long axis ultrasound clips and showed good agreement with manually traced contours. Thus, this study demonstrates that detection of anatomic markers leads to a reliable initial guess of the left ventricle border.

##### Abstract (translated by Google)
左心室分割对于测量左心室功能指数是必不可少的。一个或多个图像的分割需要对轮廓进行初始猜测。这里假设通过首先检测解剖学标记来产生初始猜测将会导致对心内膜的正确检测。这里介绍的算法的第一步包括自动检测二尖瓣。接下来，在同一帧中检测到顶点。然后在整个心动周期中追踪瓣膜。然后使用动态编程算法找到从顶点到每个阀角的轮廓。生成的轮廓用作活动轮廓算法的输入。该算法在21个长轴超声夹上进行测试，并与人工描绘的轮廓显示出良好的一致性。因此，这项研究表明，解剖标志的检测导致左心室边界的可靠的初步猜测。

##### URL
[https://arxiv.org/abs/1510.03250](https://arxiv.org/abs/1510.03250)

##### PDF
[https://arxiv.org/pdf/1510.03250](https://arxiv.org/pdf/1510.03250)

