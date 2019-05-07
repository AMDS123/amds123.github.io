---
layout: post
title: "Multi-Evidence Filtering and Fusion for Multi-Label Classification, Object Detection and Semantic Segmentation Based on Weakly Supervised Learning"
date: 2018-02-26 02:07:19
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Weakly_Supervised Image_Classification Semantic_Segmentation Classification Prediction Detection Recognition
author: Weifeng Ge, Sibei Yang, Yizhou Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Supervised object detection and semantic segmentation require object or even pixel level annotations. When there exist image level labels only, it is challenging for weakly supervised algorithms to achieve accurate predictions. The accuracy achieved by top weakly supervised algorithms is still significantly lower than their fully supervised counterparts. In this paper, we propose a novel weakly supervised curriculum learning pipeline for multi-label object recognition, detection and semantic segmentation. In this pipeline, we first obtain intermediate object localization and pixel labeling results for the training images, and then use such results to train task-specific deep networks in a fully supervised manner. The entire process consists of four stages, including object localization in the training images, filtering and fusing object instances, pixel labeling for the training images, and task-specific network training. To obtain clean object instances in the training images, we propose a novel algorithm for filtering, fusing and classifying object instances collected from multiple solution mechanisms. In this algorithm, we incorporate both metric learning and density-based clustering to filter detected object instances. Experiments show that our weakly supervised pipeline achieves state-of-the-art results in multi-label image classification as well as weakly supervised object detection and very competitive results in weakly supervised semantic segmentation on MS-COCO, PASCAL VOC 2007 and PASCAL VOC 2012.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1802.09129](https://arxiv.org/abs/1802.09129)

##### PDF
[https://arxiv.org/pdf/1802.09129](https://arxiv.org/pdf/1802.09129)

