---
layout: post
title: "PCL: Proposal Cluster Learning for Weakly Supervised Object Detection"
date: 2018-10-13 18:28:09
categories: arXiv_CV
tags: arXiv_CV Object_Detection Weakly_Supervised CNN Image_Classification Classification Detection Recognition
author: Peng Tang, Xinggang Wang, Song Bai, Wei Shen, Xiang Bai, Wenyu Liu, Alan Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
Weakly Supervised Object Detection (WSOD), using only image-level annotations to train object detectors, is of growing importance in object recognition. In this paper, we propose a novel deep network for WSOD. Unlike previous networks that transfer the object detection problem to an image classification problem using Multiple Instance Learning (MIL), our strategy generates proposal clusters to learn refined instance classifiers by an iterative process. The proposals in the same cluster are spatially adjacent and associated with the same object. This prevents the network from concentrating too much on parts of objects instead of whole objects. We first show that instances can be assigned object or background labels directly based on proposal clusters for instance classifier refinement, and then show that treating each cluster as a small new bag yields fewer ambiguities than the directly assigning label method. The iterative instance classifier refinement is implemented online using multiple streams in convolutional neural networks, where the first is an MIL network and the others are for instance classifier refinement supervised by the preceding one. Experiments are conducted on the PASCAL VOC, ImageNet detection, and MS-COCO benchmarks for WSOD. Results show that our method outperforms the previous state of the art significantly.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1807.03342](https://arxiv.org/abs/1807.03342)

##### PDF
[https://arxiv.org/pdf/1807.03342](https://arxiv.org/pdf/1807.03342)

