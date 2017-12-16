---
layout: post
title: "Depth estimation using structured light flow -- analysis of projected pattern flow on an object's surface --"
date: 2017-10-02 07:27:22
categories: arXiv_CV
tags: arXiv_CV Face
author: Ryo Furukawa, Ryusuke Sagawa, Hiroshi Kawasaki
mathjax: true
---

* content
{:toc}

##### Abstract
Shape reconstruction techniques using structured light have been widely researched and developed due to their robustness, high precision, and density. Because the techniques are based on decoding a pattern to find correspondences, it implicitly requires that the projected patterns be clearly captured by an image sensor, i.e., to avoid defocus and motion blur of the projected pattern. Although intensive researches have been conducted for solving defocus blur, few researches for motion blur and only solution is to capture with extremely fast shutter speed. In this paper, unlike the previous approaches, we actively utilize motion blur, which we refer to as a light flow, to estimate depth. Analysis reveals that minimum two light flows, which are retrieved from two projected patterns on the object, are required for depth estimation. To retrieve two light flows at the same time, two sets of parallel line patterns are illuminated from two video projectors and the size of motion blur of each line is precisely measured. By analyzing the light flows, i.e. lengths of the blurs, scene depth information is estimated. In the experiments, 3D shapes of fast moving objects, which are inevitably captured with motion blur, are successfully reconstructed by our technique.

##### Abstract (translated by Google)
采用结构光的形状重建技术由于其鲁棒性，高精度和高密度而得到了广泛的研究和开发。由于这些技术是基于对图案进行解码以找到对应关系的，所以隐含地要求投影图案被图像传感器清楚地捕获，即避免投影图案的散焦和运动模糊。尽管已经对散焦模糊进行了深入的研究，但对于运动模糊和唯一的解决方案的研究很少，而且是以极快的快门速度进行拍摄。在本文中，与以前的方法不同，我们主动利用运动模糊（我们称之为光流）来估计深度。分析表明，深度估计需要从物体上的两个投影图案中检索的最小两个光流。为了同时检索两个光流，从两个视频投影仪照亮两组平行线图案，并精确测量每条线的运动模糊的大小。通过分析光流，即模糊的长度，估计场景深度信息。在实验中，通过我们的技术成功地重建了运动模糊中不可避免捕获的快速运动物体的三维形状。

##### URL
[https://arxiv.org/abs/1710.00513](https://arxiv.org/abs/1710.00513)

##### PDF
[https://arxiv.org/pdf/1710.00513](https://arxiv.org/pdf/1710.00513)

