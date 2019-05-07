---
layout: post
title: "A 3D Object Detection and Pose Estimation Pipeline Using RGB-D Images"
date: 2017-03-11 10:09:02
categories: arXiv_CV
tags: arXiv_CV Object_Detection Pose_Estimation Detection
author: Ruotao He, Juan Rojas, Yisheng Guan
mathjax: true
---

* content
{:toc}

##### Abstract
3D object detection and pose estimation has been studied extensively in recent decades for its potential applications in robotics. However, there still remains challenges when we aim at detecting multiple objects while retaining low false positive rate in cluttered environments. This paper proposes a robust 3D object detection and pose estimation pipeline based on RGB-D images, which can detect multiple objects simultaneously while reducing false positives. Detection begins with template matching and yields a set of template matches. A clustering algorithm then groups templates of similar spatial location and produces multiple-object hypotheses. A scoring function evaluates the hypotheses using their associated templates and non-maximum suppression is adopted to remove duplicate results based on the scores. Finally, a combination of point cloud processing algorithms are used to compute objects' 3D poses. Existing object hypotheses are verified by computing the overlap between model and scene points. Experiments demonstrate that our approach provides competitive results comparable to the state-of-the-arts and can be applied to robot random bin-picking.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1703.03940](https://arxiv.org/abs/1703.03940)

##### PDF
[https://arxiv.org/pdf/1703.03940](https://arxiv.org/pdf/1703.03940)

