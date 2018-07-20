---
layout: post
title: "Real-Time Stereo Vision for Road Surface 3-D Reconstruction"
date: 2018-07-18 06:44:07
categories: arXiv_CV
tags: arXiv_CV Face Relation
author: Rui Fan, Yanan Liu, Xingrui Yang, Mohammud Junaid Bocus, Naim Dahnoun, Scott Tancock
mathjax: true
---

* content
{:toc}

##### Abstract
Stereo vision techniques have been widely used in civil engineering to acquire 3-D road data. The two important factors of stereo vision are accuracy and speed. However, it is very challenging to achieve both of them simultaneously and therefore the main aim of developing a stereo vision system is to improve the trade-off between these two factors. In this paper, we present a real-time stereo vision system used for road surface 3-D reconstruction. The proposed system is developed from our previously published 3-D reconstruction algorithm where the perspective view of the target image is first transformed into the reference view, which not only increases the disparity accuracy but also improves the processing speed. Then, the correlation cost between each pair of blocks is computed and stored in two 3-D cost volumes. To adaptively aggregate the matching costs from neighbourhood systems, bilateral filtering is performed on the cost volumes. This greatly reduces the ambiguities during stereo matching and further improves the precision of the estimated disparities. Finally, the subpixel resolution is achieved by conducting a parabola interpolation and the subpixel disparity map is used to reconstruct the 3-D road surface. The proposed algorithm is implemented on an NVIDIA GTX 1080 GPU for the real-time purpose. The experimental results illustrate that the reconstruction accuracy is around 3 mm.

##### Abstract (translated by Google)
立体视觉技术已被广泛用于土木工程中以获取三维道路数据。立体视觉的两个重要因素是准确性和速度。然而，同时实现这两者是非常具有挑战性的，因此开发立体视觉系统的主要目的是改善这两个因素之间的权衡。在本文中，我们提出了一种用于路面三维重建的实时立体视觉系统。所提出的系统是从我们先前公布的3-D重建算法开发的，其中目标图像的透视图首先被变换到参考视图，这不仅增加了视差精度而且提高了处理速度。然后，计算每对块之间的相关成本并将其存储在两个3-D成本量中。为了自适应地聚合来自邻域系统的匹配成本，对成本量执行双边过滤。这极大地减少了立体匹配期间的模糊，并进一步提高了估计的视差的精度。最后，通过进行抛物线插值来实现子像素分辨率，并且子像素视差图用于重建3-D路面。所提出的算法在NVIDIA GTX 1080 GPU上实现，以实现实时目的。实验结果表明，重建精度约为3 mm。

##### URL
[https://arxiv.org/abs/1807.07433](https://arxiv.org/abs/1807.07433)

##### PDF
[https://arxiv.org/pdf/1807.07433](https://arxiv.org/pdf/1807.07433)

