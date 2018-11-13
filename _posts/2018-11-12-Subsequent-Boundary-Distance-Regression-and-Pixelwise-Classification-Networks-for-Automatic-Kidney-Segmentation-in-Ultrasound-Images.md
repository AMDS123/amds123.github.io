---
layout: post
title: "Subsequent Boundary Distance Regression and Pixelwise Classification Networks for Automatic Kidney Segmentation in Ultrasound Images"
date: 2018-11-12 15:54:59
categories: arXiv_CV
tags: arXiv_CV Segmentation Classification Deep_Learning
author: Shi Yin, Qinmu Peng, Hongming Li, Zhengqiang Zhang, Xinge You, Susan L. Furth, Gregory E. Tasian, Yong Fan
mathjax: true
---

* content
{:toc}

##### Abstract
It remains challenging to automatically segment kidneys in clinical ultrasound (US) images due to the kidneys' varied shapes and image intensity distributions, although semi-automatic methods have achieved promising performance. In this study, we propose subsequent boundary distance regression and pixel classification networks to segment the kidneys, informed by the fact that the kidney boundaries have relatively homogenous texture patterns across images. Particularly, we first use deep neural networks pre-trained for classification of natural images to extract high-level image features from US images, then these features are used as input to learn kidney boundary distance maps using a boundary distance regression network, and finally the predicted boundary distance maps are classified as kidney pixels or non-kidney pixels using a pixel classification network in an end-to-end learning fashion. We also proposed a novel data-augmentation method based on kidney shape registration to generate enriched training data from a small number of US images with manually segmented kidney labels. Experimental results have demonstrated that our method could effectively improve the performance of automatic kidney segmentation, significantly better than deep learning based pixel classification networks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.04815](http://arxiv.org/abs/1811.04815)

##### PDF
[http://arxiv.org/pdf/1811.04815](http://arxiv.org/pdf/1811.04815)

