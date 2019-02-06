---
layout: post
title: "6D Object Pose Estimation without PnP"
date: 2019-02-05 15:04:36
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation CNN Detection
author: Jin Liu
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose an efficient end-to-end algorithm to tackle the problem of estimating the 6D pose of objects from a single RGB image. Our system trains a fully convolutional network to regress the 3D rotation and the 3D translation in region layer. On this basis, a special layer, Collinear Equation Layer, is added next to region layer to output the 2D projections of the 3D bounding boxs corners. In the back propagation stage, the 6D pose network are adjusted according to the error of the 2D projections. In the detection phase, we directly output the position and pose through the region layer. Besides, we introduce a novel and concise representation of 3D rotation to make the regression more precise and easier. Experiments show that our method outperforms base-line and state of the art methods both at accuracy and efficiency. In the LineMod dataset, our algorithm achieves less than 18 ms/object on a GeForce GTX 1080Ti GPU, while the translational error and rotational error are less than 1.67 cm and 2.5 degree.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.01728](http://arxiv.org/abs/1902.01728)

##### PDF
[http://arxiv.org/pdf/1902.01728](http://arxiv.org/pdf/1902.01728)

