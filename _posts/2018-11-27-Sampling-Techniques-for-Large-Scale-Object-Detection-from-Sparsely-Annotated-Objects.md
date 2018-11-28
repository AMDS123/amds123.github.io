---
layout: post
title: "Sampling Techniques for Large-Scale Object Detection from Sparsely Annotated Objects"
date: 2018-11-27 08:14:02
categories: arXiv_CV
tags: arXiv_CV Object_Detection Sparse Detection Relation
author: Yusuke Niitani, Takuya Akiba, Tommi Kerola, Toru Ogawa, Shotaro Sano, Shuji Suzuki
mathjax: true
---

* content
{:toc}

##### Abstract
Efficient and reliable methods for training of object detectors are in higher demand than ever, and more and more data relevant to the field is becoming available. However, large datasets like Open Images Dataset v4 (OID) are sparsely annotated, and some measure must be taken in order to ensure the training of a reliable detector. In order to take the incompleteness of these datasets into account, one possibility is to use pretrained models to detect the presence of the unverified objects. However, the performance of such a strategy depends largely on the power of the pretrained model. In this study, we propose part-aware sampling, a method that uses human intuition for the hierarchical relation between objects. In terse terms, our method works by making assumptions like "a bounding box for a car should contain a bounding box for a tire". We demonstrate the power of our method on OID and compare the performance against a method based on a pretrained model. Our method also won the first and second place on the public and private test sets of the Google AI Open Images Competition 2018.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.10862](http://arxiv.org/abs/1811.10862)

##### PDF
[http://arxiv.org/pdf/1811.10862](http://arxiv.org/pdf/1811.10862)

