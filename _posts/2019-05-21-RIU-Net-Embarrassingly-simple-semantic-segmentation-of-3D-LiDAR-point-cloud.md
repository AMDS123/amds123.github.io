---
layout: post
title: "RIU-Net: Embarrassingly simple semantic segmentation of 3D LiDAR point cloud"
date: 2019-05-21 16:51:35
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Semantic_Segmentation Detection
author: Pierre Biasutti, Aur&#xe9;lie Bugeau, Jean-Fran&#xe7;ois Aujol, Mathieu Br&#xe9;dif
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes RIU-Net (for Range-Image U-Net), the adaptation of a popular semantic segmentation network for the semantic segmentation of a 3D LiDAR point cloud. The point cloud is turned into a 2D range-image by exploiting the topology of the sensor. This image is then used as input to a U-net. This architecture has already proved its efficiency for the task of semantic segmentation of medical images. We propose to demonstrate how it can also be used for the accurate semantic segmentation of a 3D LiDAR point cloud. Our model is trained on range-images built from KITTI 3D object detection dataset. Experiments show that RIU-Net, despite being very simple, outperforms the state-of-the-art of range-image based methods. Finally, we demonstrate that this architecture is able to operate at 90fps on a single GPU, which enables deployment on low computational power systems such as robots.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.08748](http://arxiv.org/abs/1905.08748)

##### PDF
[http://arxiv.org/pdf/1905.08748](http://arxiv.org/pdf/1905.08748)

