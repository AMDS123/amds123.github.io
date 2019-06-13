---
layout: post
title: "Handwritten Text Segmentation via End-to-End Learning of Convolutional Neural Network"
date: 2019-06-12 16:03:57
categories: arXiv_CV
tags: arXiv_CV OCR Segmentation CNN
author: Junho Jo, Hyung Il Koo, Jae Woong Soh, Nam Ik Cho
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new handwritten text segmentation method by training a convolutional neural network (CNN) in an end-to-end manner. Many conventional methods addressed this problem by extracting connected components and then classifying them. However, this two-step approach has limitations when handwritten components and machine-printed parts are overlapping. Unlike conventional methods, we develop an end-to-end deep CNN for this problem, which does not need any preprocessing steps. Since there is no publicly available dataset for this goal and pixel-wise annotations are time-consuming and costly, we also propose a data synthesis algorithm that generates realistic training samples. For training our network, we develop a cross-entropy based loss function that addresses the imbalance problems. Experimental results on synthetic and real images show the effectiveness of the proposed method. Specifically, the proposed network has been trained solely on synthetic images, nevertheless the removal of handwritten text in real documents improves OCR performance from 71.13% to 92.50%, showing the generalization performance of our network and synthesized images.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.05229](http://arxiv.org/abs/1906.05229)

##### PDF
[http://arxiv.org/pdf/1906.05229](http://arxiv.org/pdf/1906.05229)

