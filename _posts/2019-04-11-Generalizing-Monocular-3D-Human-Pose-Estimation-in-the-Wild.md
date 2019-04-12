---
layout: post
title: "Generalizing Monocular 3D Human Pose Estimation in the Wild"
date: 2019-04-11 03:18:15
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Quantitative
author: Luyang Wang, Yan Chen, Zhenhua Guo, Keyuan Qian, Mude Lin, Hongsheng Li, Jimmy S. Ren
mathjax: true
---

* content
{:toc}

##### Abstract
The availability of the large-scale labeled 3D poses in the Human3.6M dataset plays an important role in advancing the algorithms for 3D human pose estimation from a still image. We observe that recent innovation in this area mainly focuses on new techniques that explicitly address the generalization issue when using this dataset, because this database is constructed in a highly controlled environment with limited human subjects and background variations. Despite such efforts, we can show that the results of the current methods are still error-prone especially when tested against the images taken in-the-wild. In this paper, we aim to tackle this problem from a different perspective. We propose a principled approach to generate high quality 3D pose ground truth given any in-the-wild image with a person inside. We achieve this by first devising a novel stereo inspired neural network to directly map any 2D pose to high quality 3D counterpart. We then perform a carefully designed geometric searching scheme to further refine the joints. Based on this scheme, we build a large-scale dataset with 400,000 in-the-wild images and their corresponding 3D pose ground truth. This enables the training of a high quality neural network model, without specialized training scheme and auxiliary loss function, which performs favorably against the state-of-the-art 3D pose estimation methods. We also evaluate the generalization ability of our model both quantitatively and qualitatively. Results show that our approach convincingly outperforms the previous methods. We make our dataset and code publicly available.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.05512](http://arxiv.org/abs/1904.05512)

##### PDF
[http://arxiv.org/pdf/1904.05512](http://arxiv.org/pdf/1904.05512)

