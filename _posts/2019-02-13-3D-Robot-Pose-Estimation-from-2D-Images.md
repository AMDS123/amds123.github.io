---
layout: post
title: "3D Robot Pose Estimation from 2D Images"
date: 2019-02-13 16:26:31
categories: arXiv_CV
tags: arXiv_CV Object_Detection Sparse Pose_Estimation CNN Detection
author: Christoph Heindl, Sebastian Zambal, Thomas Ponitz, Andreas Pichler, Josef Scharinger
mathjax: true
---

* content
{:toc}

##### Abstract
This paper considers the task of locating articulated poses of multiple robots in images. Our approach simultaneously infers the number of robots in a scene, identifies joint locations and estimates sparse depth maps around joint locations. The proposed method applies staged convolutional feature detectors to 2D image inputs and computes robot instance masks using a recurrent network architecture. In addition, regression maps of most likely joint locations in pixel coordinates together with depth information are computed. Compositing 3D robot joint kinematics is accomplished by applying masks to joint readout maps. Our end-to-end formulation is in contrast to previous work in which the composition of robot joints into kinematics is performed in a separate post-processing step. Despite the fact that our models are trained on artificial data, we demonstrate generalizability to real world images.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.04987](http://arxiv.org/abs/1902.04987)

##### PDF
[http://arxiv.org/pdf/1902.04987](http://arxiv.org/pdf/1902.04987)

