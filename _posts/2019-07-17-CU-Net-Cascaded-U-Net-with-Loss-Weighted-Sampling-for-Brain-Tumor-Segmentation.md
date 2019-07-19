---
layout: post
title: "CU-Net: Cascaded U-Net with Loss Weighted Sampling for Brain Tumor Segmentation"
date: 2019-07-17 10:16:04
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Hongying Liu, Xiongjie Shen, Fanhua Shang, Fei Wang
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a novel cascaded U-Net for brain tumor segmentation. Inspired by the distinct hierarchical structure of brain tumor, we design a cascaded deep network framework, in which the whole tumor is segmented firstly and then the tumor internal substructures are further segmented. Considering that the increase of the network depth brought by cascade structures leads to a loss of accurate localization information in deeper layers, we construct many skip connections to link features at the same resolution and transmit detailed information from shallow layers to the deeper layers. Then we present a loss weighted sampling (LWS) scheme to eliminate the issue of imbalanced data during training the network. Experimental results on BraTS 2017 data show that our architecture framework outperforms the state-of-the-art segmentation algorithms, especially in terms of segmentation sensitivity.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.07677](http://arxiv.org/abs/1907.07677)

##### PDF
[http://arxiv.org/pdf/1907.07677](http://arxiv.org/pdf/1907.07677)

