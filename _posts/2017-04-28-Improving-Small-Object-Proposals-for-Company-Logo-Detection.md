---
layout: post
title: "Improving Small Object Proposals for Company Logo Detection"
date: 2017-04-28 11:30:10
categories: arXiv_CV
tags: arXiv_CV Object_Detection Classification Detection
author: Christian Eggert, Dan Zecha, Stephan Brehm, Rainer Lienhart
mathjax: true
---

* content
{:toc}

##### Abstract
Many modern approaches for object detection are two-staged pipelines. The first stage identifies regions of interest which are then classified in the second stage. Faster R-CNN is such an approach for object detection which combines both stages into a single pipeline. In this paper we apply Faster R-CNN to the task of company logo detection. Motivated by its weak performance on small object instances, we examine in detail both the proposal and the classification stage with respect to a wide range of object sizes. We investigate the influence of feature map resolution on the performance of those stages. Based on theoretical considerations, we introduce an improved scheme for generating anchor proposals and propose a modification to Faster R-CNN which leverages higher-resolution feature maps for small objects. We evaluate our approach on the FlickrLogos dataset improving the RPN performance from 0.52 to 0.71 (MABO) and the detection performance from 0.52 to 0.67 (mAP).

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1704.08881](https://arxiv.org/abs/1704.08881)

##### PDF
[https://arxiv.org/pdf/1704.08881](https://arxiv.org/pdf/1704.08881)

