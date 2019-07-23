---
layout: post
title: "Multi-scale Cell Instance Segmentation with Keypoint Graph based Bounding Boxes"
date: 2019-07-22 05:25:01
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Detection
author: Jingru Yi, Pengxiang Wu, Qiaoying Huang, Hui Qu, Bo Liu, Daniel J. Hoeppner, Dimitris N. Metaxas
mathjax: true
---

* content
{:toc}

##### Abstract
Most existing methods handle cell instance segmentation problems directly without relying on additional detection boxes. This method generally fails to separate touching cells due to the lack of global understanding of the objects. In contrast, box-based instance segmentation solves this problem by combining object detection with segmentation. However, existing methods typically utilize anchor box-based detectors, which would lead to inferior instance segmentation performance due to the class imbalance issue. In this paper, we propose a new box-based cell instance segmentation method. In particular, we first detect the five pre-defined points of a cell via keypoints detection. Then we group these points according to a keypoint graph and subsequently extract the bounding box for each cell. Finally, cell segmentation is performed on feature maps within the bounding boxes. We validate our method on two cell datasets with distinct object shapes, and empirically demonstrate the superiority of our method compared to other instance segmentation techniques. Code is available at: https://github.com/yijingru/KG_Instance_Segmentation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.09140](http://arxiv.org/abs/1907.09140)

##### PDF
[http://arxiv.org/pdf/1907.09140](http://arxiv.org/pdf/1907.09140)

