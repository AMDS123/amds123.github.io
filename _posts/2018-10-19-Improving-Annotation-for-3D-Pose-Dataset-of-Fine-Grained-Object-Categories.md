---
layout: post
title: "Improving Annotation for 3D Pose Dataset of Fine-Grained Object Categories"
date: 2018-10-19 01:48:05
categories: arXiv_CV
tags: arXiv_CV Segmentation Pose_Estimation CNN Quantitative Recognition
author: Yaming Wang, Xiao Tan, Yi Yang, Ziyu Li, Xiao Liu, Feng Zhou, Larry S. Davis
mathjax: true
---

* content
{:toc}

##### Abstract
Existing 3D pose datasets of object categories are limited to generic object types and lack of fine-grained information. In this work, we introduce a new large-scale dataset that consists of 409 fine-grained categories and 31,881 images with accurate 3D pose annotation. Specifically, we augment three existing fine-grained object recognition datasets (StanfordCars, CompCars and FGVC-Aircraft) by finding a specific 3D model for each sub-category from ShapeNet and manually annotating each 2D image by adjusting a full set of 7 continuous perspective parameters. Since the fine-grained shapes allow 3D models to better fit the images, we further improve the annotation quality by initializing from the human annotation and conducting local search of the pose parameters with the objective of maximizing the IoUs between the projected mask and the segmentation reference estimated from state-of-the-art deep Convolutional Neural Networks (CNNs). We provide full statistics of the annotations with qualitative and quantitative comparisons suggesting that our dataset can be a complementary source for studying 3D pose estimation. The dataset can be downloaded at <a href="http://users.umiacs.umd.edu/~wym/3dpose.html.">this http URL</a>

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.09263](http://arxiv.org/abs/1810.09263)

##### PDF
[http://arxiv.org/pdf/1810.09263](http://arxiv.org/pdf/1810.09263)

