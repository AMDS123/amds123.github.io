---
layout: post
title: "SweepNet: Wide-baseline Omnidirectional Depth Estimation"
date: 2019-02-28 05:36:19
categories: arXiv_CV
tags: arXiv_CV CNN
author: Changhee Won, Jongbin Ryu, Jongwoo Lim
mathjax: true
---

* content
{:toc}

##### Abstract
Omnidirectional depth sensing has its advantage over the conventional stereo systems since it enables us to recognize the objects of interest in all directions without any blind regions. In this paper, we propose a novel wide-baseline omnidirectional stereo algorithm which computes the dense depth estimate from the fisheye images using a deep convolutional neural network. The capture system consists of multiple cameras mounted on a wide-baseline rig with ultrawide field of view (FOV) lenses, and we present the calibration algorithm for the extrinsic parameters based on the bundle adjustment. Instead of estimating depth maps from multiple sets of rectified images and stitching them, our approach directly generates one dense omnidirectional depth map with full 360-degree coverage at the rig global coordinate system. To this end, the proposed neural network is designed to output the cost volume from the warped images in the sphere sweeping method, and the final depth map is estimated by taking the minimum cost indices of the aggregated cost volume by SGM. For training the deep neural network and testing the entire system, realistic synthetic urban datasets are rendered using Blender. The experiments using the synthetic and real-world datasets show that our algorithm outperforms the conventional depth estimation methods and generate highly accurate depth maps.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.10904](http://arxiv.org/abs/1902.10904)

##### PDF
[http://arxiv.org/pdf/1902.10904](http://arxiv.org/pdf/1902.10904)

