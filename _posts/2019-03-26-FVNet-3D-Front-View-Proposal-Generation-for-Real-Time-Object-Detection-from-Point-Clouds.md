---
layout: post
title: "FVNet: 3D Front-View Proposal Generation for Real-Time Object Detection from Point Clouds"
date: 2019-03-26 09:26:46
categories: arXiv_CV
tags: arXiv_CV Object_Detection Sparse Face Inference Detection
author: Jie Zhou, Xuequan Lu, Xin Tan, Zhiwei Shao, Shouhong Ding, Lizhuang Ma
mathjax: true
---

* content
{:toc}

##### Abstract
3D object detection from raw and sparse point clouds has been far less treated to date, compared with its 2D counterpart. In this paper, we propose a novel framework called FVNet for 3D front-view proposal generation and object detection from point clouds. It consists of two stages: generation of front-view proposals and estimation of 3D bounding box parameters. Instead of generating proposals from camera images or bird's-eye-view maps, we first project point clouds onto a cylindrical surface to generate front-view feature maps which retains rich information. We then introduce a proposal generation network to predict 3D region proposals from the generated maps and further extrude objects of interest from the whole point cloud. Finally, we present another network to extract the point-wise features from the extruded object points and regress the final 3D bounding box parameters in the canonical coordinates. Our framework achieves real-time performance with 12ms per point cloud sample. Extensive experiments on the 3D detection benchmark KITTI show that the proposed architecture outperforms state-of-the-art techniques which take either camera images or point clouds as input, in terms of accuracy and inference time.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.10750](http://arxiv.org/abs/1903.10750)

##### PDF
[http://arxiv.org/pdf/1903.10750](http://arxiv.org/pdf/1903.10750)

