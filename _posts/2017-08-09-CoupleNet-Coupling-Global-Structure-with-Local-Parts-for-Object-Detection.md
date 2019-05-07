---
layout: post
title: "CoupleNet: Coupling Global Structure with Local Parts for Object Detection"
date: 2017-08-09 15:07:23
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Classification Detection
author: Yousong Zhu, Chaoyang Zhao, Jinqiao Wang, Xu Zhao, Yi Wu, Hanqing Lu
mathjax: true
---

* content
{:toc}

##### Abstract
The region-based Convolutional Neural Network (CNN) detectors such as Faster R-CNN or R-FCN have already shown promising results for object detection by combining the region proposal subnetwork and the classification subnetwork together. Although R-FCN has achieved higher detection speed while keeping the detection performance, the global structure information is ignored by the position-sensitive score maps. To fully explore the local and global properties, in this paper, we propose a novel fully convolutional network, named as CoupleNet, to couple the global structure with local parts for object detection. Specifically, the object proposals obtained by the Region Proposal Network (RPN) are fed into the the coupling module which consists of two branches. One branch adopts the position-sensitive RoI (PSRoI) pooling to capture the local part information of the object, while the other employs the RoI pooling to encode the global and context information. Next, we design different coupling strategies and normalization ways to make full use of the complementary advantages between the global and local branches. Extensive experiments demonstrate the effectiveness of our approach. We achieve state-of-the-art results on all three challenging datasets, i.e. a mAP of 82.7% on VOC07, 80.4% on VOC12, and 34.4% on COCO. Codes will be made publicly available.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1708.02863](https://arxiv.org/abs/1708.02863)

##### PDF
[https://arxiv.org/pdf/1708.02863](https://arxiv.org/pdf/1708.02863)

