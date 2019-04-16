---
layout: post
title: "Leveraging Pre-Trained 3D Object Detection Models For Fast Ground Truth Generation"
date: 2018-07-16 19:33:09
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Detection
author: Jungwook Lee, Sean Walsh, Ali Harakeh, Steven L. Waslander
mathjax: true
---

* content
{:toc}

##### Abstract
Training 3D object detectors for autonomous driving has been limited to small datasets due to the effort required to generate annotations. Reducing both task complexity and the amount of task switching done by annotators is key to reducing the effort and time required to generate 3D bounding box annotations. This paper introduces a novel ground truth generation method that combines human supervision with pretrained neural networks to generate per-instance 3D point cloud segmentation, 3D bounding boxes, and class annotations. The annotators provide object anchor clicks which behave as a seed to generate instance segmentation results in 3D. The points belonging to each instance are then used to regress object centroids, bounding box dimensions, and object orientation. Our proposed annotation scheme requires 30x lower human annotation time. We use the KITTI 3D object detection dataset to evaluate the efficiency and the quality of our annotation scheme. We also test the the proposed scheme on previously unseen data from the Autonomoose self-driving vehicle to demonstrate generalization capabilities of the network.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1807.06072](https://arxiv.org/abs/1807.06072)

##### PDF
[https://arxiv.org/pdf/1807.06072](https://arxiv.org/pdf/1807.06072)

