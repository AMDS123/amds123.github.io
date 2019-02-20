---
layout: post
title: "Multi-view Incremental Segmentation of 3D Point Clouds for Mobile Robots"
date: 2019-02-18 19:18:38
categories: arXiv_RO
tags: arXiv_RO Segmentation Semantic_Segmentation Classification
author: Jingdao Chen, Yong K. Cho, Zsolt Kira
mathjax: true
---

* content
{:toc}

##### Abstract
Mobile robots need to create high-definition 3D maps of the environment for applications such as remote surveillance and infrastructure mapping. Accurate semantic processing of the acquired 3D point cloud is critical for allowing the robot to obtain a high-level understanding of the surrounding objects and perform context-aware decision making. Existing techniques for point cloud semantic segmentation are mostly applied on a single-frame or offline basis, with no way to integrate the segmentation results over time. This paper proposes an online method for mobile robots to incrementally build a semantically-rich 3D point cloud of the environment. The proposed deep neural network, MCPNet, is trained to predict class labels and object instance labels for each point in the scanned point cloud in an incremental fashion. A multi-view context pooling (MCP) operator is used to combine point features obtained from multiple viewpoints to improve the classification accuracy. The proposed architecture was trained and evaluated on ray-traced scans derived from the Stanford 3D Indoor Spaces dataset. Results show that the proposed approach led to 15% improvement in point-wise accuracy and 7% improvement in NMI compared to the next best online method, with only a 6% drop in accuracy compared to the PointNet-based offline approach.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.06768](http://arxiv.org/abs/1902.06768)

##### PDF
[http://arxiv.org/pdf/1902.06768](http://arxiv.org/pdf/1902.06768)

