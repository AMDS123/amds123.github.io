---
layout: post
title: "Learning from Web Data: the Benefit of Unsupervised Object Localization"
date: 2018-12-21 16:25:20
categories: arXiv_CV
tags: arXiv_CV Image_Classification Classification
author: Xiaoxiao Sun, Liang Zheng, Yu-Kun Lai, Jufeng Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Annotating a large number of training images is very time-consuming. In this background, this paper focuses on learning from easy-to-acquire web data and utilizes the learned model for fine-grained image classification in labeled datasets. Currently, the performance gain from training with web data is incremental, like a common saying "better than nothing, but not by much". Conventionally, the community looks to correcting the noisy web labels to select informative samples. In this work, we first systematically study the built-in gap between the web and standard datasets, i.e. different data distributions between the two kinds of data. Then, in addition to using web labels, we present an unsupervised object localization method, which provides critical insights into the object density and scale in web images. Specifically, we design two constraints on web data to substantially reduce the difference of data distributions for the web and standard datasets. First, we present a method to control the scale, localization and number of objects in the detected region. Second, we propose to select the regions containing objects that are consistent with the web tag. Based on the two constraints, we are able to process web images to reduce the gap, and the processed web data is used to better assist the standard dataset to train CNNs. Experiments on several fine-grained image classification datasets confirm that our method performs favorably against the state-of-the-art methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.09232](http://arxiv.org/abs/1812.09232)

##### PDF
[http://arxiv.org/pdf/1812.09232](http://arxiv.org/pdf/1812.09232)

