---
layout: post
title: "Benchmark data and method for real-time people counting in cluttered scenes using depth sensors"
date: 2018-10-28 07:45:37
categories: arXiv_CV
tags: arXiv_CV
author: ShiJie Sun, Naveed Akhtar, HuanSheng Song, ChaoYang Zhang, JianXin Li, Ajmal Mian
mathjax: true
---

* content
{:toc}

##### Abstract
Vision-based automatic counting of people has widespread applications in intelligent transportation systems, security, and logistics. However, there is currently no large-scale public dataset for benchmarking approaches on this problem. This work fills this gap by introducing the first real-world RGB-D People Counting DataSet (PCDS) containing over 4,500 videos recorded at the entrance doors of buses in normal and cluttered conditions. It also proposes an efficient method for counting people in real-world cluttered scenes related to public transportations using depth videos. The proposed method computes a point cloud from the depth video frame and re-projects it onto the ground plane to normalize the depth information. The resulting depth image is analyzed for identifying potential human heads. The human head proposals are meticulously refined using a 3D human model. The proposals in each frame of the continuous video stream are tracked to trace their trajectories. The trajectories are again refined to ascertain reliable counting. People are eventually counted by accumulating the head trajectories leaving the scene. To enable effective head and trajectory identification, we also propose two different compound features. A thorough evaluation on PCDS demonstrates that our technique is able to count people in cluttered scenes with high accuracy at 45 fps on a 1.7 GHz processor, and hence it can be deployed for effective real-time people counting for intelligent transportation systems.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1804.04339](http://arxiv.org/abs/1804.04339)

##### PDF
[http://arxiv.org/pdf/1804.04339](http://arxiv.org/pdf/1804.04339)

