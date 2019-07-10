---
layout: post
title: "Positional Normalization"
date: 2019-07-09 17:52:01
categories: arXiv_CV
tags: arXiv_CV
author: Boyi Li, Felix Wu, Kilian Q. Weinberger, Serge Belongie
mathjax: true
---

* content
{:toc}

##### Abstract
A widely deployed method for reducing the training time of deep neural networks is to normalize activations at each layer. Although various normalization schemes have been proposed, they all follow a common theme: normalize across spatial dimensions and discard the extracted statistics. In this paper, we propose a novel normalization method that noticeably departs from this convention. Our approach, which we refer to as Positional Normalization (PONO), normalizes exclusively across channels --- a naturally appealing dimension, which captures the first and second moments of features extracted at a particular image position. We argue that these moments convey structural information about the input image and the extracted features, which opens a new avenue along which a network can benefit from feature normalization: Instead of disregarding the PONO normalization constants, we propose to re-inject them into later layers to preserve or transfer structural information in generative networks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.04312](http://arxiv.org/abs/1907.04312)

##### PDF
[http://arxiv.org/pdf/1907.04312](http://arxiv.org/pdf/1907.04312)

