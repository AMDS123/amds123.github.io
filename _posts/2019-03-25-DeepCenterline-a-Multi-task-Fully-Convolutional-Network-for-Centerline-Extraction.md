---
layout: post
title: "DeepCenterline: a Multi-task Fully Convolutional Network for Centerline Extraction"
date: 2019-03-25 17:29:30
categories: arXiv_CV
tags: arXiv_CV Review Knowledge Segmentation CNN
author: Zhihui Guo, Junjie Bai, Yi Lu, Xin Wang, Kunlin Cao, Qi Song, Milan Sonka, Youbing Yin
mathjax: true
---

* content
{:toc}

##### Abstract
A novel centerline extraction framework is reported which combines an end-to-end trainable multi-task fully convolutional network (FCN) with a minimal path extractor. The FCN simultaneously computes centerline distance maps and detects branch endpoints. The method generates single-pixel-wide centerlines with no spurious branches. It handles arbitrary tree-structured object with no prior assumption regarding depth of the tree or its bifurcation pattern. It is also robust to substantial scale changes across different parts of the target object and minor imperfections of the object's segmentation mask. To the best of our knowledge, this is the first deep-learning based centerline extraction method that guarantees single-pixel-wide centerline for a complex tree-structured object. The proposed method is validated in coronary artery centerline extraction on a dataset of 620 patients (400 of which used as test set). This application is challenging due to the large number of coronary branches, branch tortuosity, and large variations in length, thickness, shape, etc. The proposed method generates well-positioned centerlines, exhibiting lower number of missing branches and is more robust in the presence of minor imperfections of the object segmentation mask. Compared to a state-of-the-art traditional minimal path approach, our method improves patient-level success rate of centerline extraction from 54.3% to 88.8% according to independent human expert review.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.10481](http://arxiv.org/abs/1903.10481)

##### PDF
[http://arxiv.org/pdf/1903.10481](http://arxiv.org/pdf/1903.10481)

