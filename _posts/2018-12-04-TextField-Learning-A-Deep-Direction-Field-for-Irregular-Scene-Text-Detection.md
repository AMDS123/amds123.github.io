---
layout: post
title: "TextField: Learning A Deep Direction Field for Irregular Scene Text Detection"
date: 2018-12-04 13:12:58
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation CNN Deep_Learning Detection
author: Yongchao Xu, Yukang Wang, Wei Zhou, Yongpan Wang, Zhibo Yang, Xiang Bai
mathjax: true
---

* content
{:toc}

##### Abstract
Scene text detection is an important step of scene text reading system. The main challenges lie on significantly varied sizes and aspect ratios, arbitrary orientations and shapes. Driven by recent progress in deep learning, impressive performances have been achieved for multi-oriented text detection. Yet, the performance drops dramatically in detecting curved texts due to the limited text representation (e.g., horizontal bounding boxes, rotated rectangles, or quadrilaterals). It is of great interest to detect curved texts, which are actually very common in natural scenes. In this paper, we present a novel text detector named TextField for detecting irregular scene texts. Specifically, we learn a direction field pointing away from the nearest text boundary to each text point. This direction field is represented by an image of two-dimensional vectors and learned via a fully convolutional neural network. It encodes both binary text mask and direction information used to separate adjacent text instances, which is challenging for classical segmentation-based approaches. Based on the learned direction field, we apply a simple yet effective morphological-based post-processing to achieve the final detection. Experimental results show that the proposed TextField outperforms the state-of-the-art methods by a large margin (28% and 8%) on two curved text datasets: Total-Text and CTW1500, respectively, and also achieves very competitive performance on multi-oriented datasets: ICDAR 2015 and MSRA-TD500. Furthermore, TextField is robust in generalizing to unseen datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.01393](http://arxiv.org/abs/1812.01393)

##### PDF
[http://arxiv.org/pdf/1812.01393](http://arxiv.org/pdf/1812.01393)

