---
layout: post
title: "Object-Aware Instance Labeling for Weakly Supervised Object Detection"
date: 2019-08-10 17:48:19
categories: arXiv_CV
tags: arXiv_CV Object_Detection Attention Weakly_Supervised Text_Classification Classification Detection
author: Satoshi Kosugi, Toshihiko Yamasaki, Kiyoharu Aizawa
mathjax: true
---

* content
{:toc}

##### Abstract
Weakly supervised object detection (WSOD), where a detector is trained with only image-level annotations, is attracting more and more attention. As a method to obtain a well-performing detector, the detector and the instance labels are updated iteratively. In this study, for more efficient iterative updating, we focus on the instance labeling problem, a problem of which label should be annotated to each region based on the last localization result. Instead of simply labeling the top-scoring region and its highly overlapping regions as positive and others as negative, we propose more effective instance labeling methods as follows. First, to solve the problem that regions covering only some parts of the object tend to be labeled as positive, we find regions covering the whole object focusing on the context classification loss. Second, considering the situation where the other objects contained in the image can be labeled as negative, we impose a spatial restriction on regions labeled as negative. Using these instance labeling methods, we train the detector on the PASCAL VOC 2007 and 2012 and obtain significantly improved results compared with other state-of-the-art approaches.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.03792](https://arxiv.org/abs/1908.03792)

##### PDF
[https://arxiv.org/pdf/1908.03792](https://arxiv.org/pdf/1908.03792)

