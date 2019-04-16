---
layout: post
title: "Speeding-up Object Detection Training for Robotics with FALKON"
date: 2018-08-27 15:19:38
categories: arXiv_CV
tags: arXiv_CV Object_Detection Deep_Learning Detection
author: Elisa Maiettini, Giulia Pasquale, Lorenzo Rosasco, Lorenzo Natale
mathjax: true
---

* content
{:toc}

##### Abstract
Latest deep learning methods for object detection provide remarkable performance, but have limits when used in robotic applications. One of the most relevant issues is the long training time, which is due to the large size and imbalance of the associated training sets, characterized by few positive and a large number of negative examples (i.e. background). Proposed approaches are based on end-to-end learning by back-propagation [22] or kernel methods trained with Hard Negatives Mining on top of deep features [8]. These solutions are effective, but prohibitively slow for on-line applications. In this paper we propose a novel pipeline for object detection that overcomes this problem and provides comparable performance, with a 60x training speedup. Our pipeline combines (i) the Region Proposal Network and the deep feature extractor from [22] to efficiently select candidate RoIs and encode them into powerful representations, with (ii) the FALKON [23] algorithm, a novel kernel-based method that allows fast training on large scale problems (millions of points). We address the size and imbalance of training data by exploiting the stochastic subsampling intrinsic into the method and a novel, fast, bootstrapping approach. We assess the effectiveness of the approach on a standard Computer Vision dataset (PASCAL VOC 2007 [5]) and demonstrate its applicability to a real robotic scenario with the iCubWorld Transformations [18] dataset.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1803.08740](https://arxiv.org/abs/1803.08740)

##### PDF
[https://arxiv.org/pdf/1803.08740](https://arxiv.org/pdf/1803.08740)

