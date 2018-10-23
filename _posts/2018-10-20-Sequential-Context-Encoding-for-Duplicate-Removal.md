---
layout: post
title: "Sequential Context Encoding for Duplicate Removal"
date: 2018-10-20 08:26:32
categories: arXiv_CV
tags: arXiv_CV Object_Detection Attention RNN Prediction Detection
author: Lu Qi, Shu Liu, Jianping Shi, Jiaya Jia
mathjax: true
---

* content
{:toc}

##### Abstract
Duplicate removal is a critical step to accomplish a reasonable amount of predictions in prevalent proposal-based object detection frameworks. Albeit simple and effective, most previous algorithms utilize a greedy process without making sufficient use of properties of input data. In this work, we design a new two-stage framework to effectively select the appropriate proposal candidate for each object. The first stage suppresses most of easy negative object proposals, while the second stage selects true positives in the reduced proposal set. These two stages share the same network structure, \ie, an encoder and a decoder formed as recurrent neural networks (RNN) with global attention and context gate. The encoder scans proposal candidates in a sequential manner to capture the global context information, which is then fed to the decoder to extract optimal proposals. In our extensive experiments, the proposed method outperforms other alternatives by a large margin.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.08770](http://arxiv.org/abs/1810.08770)

##### PDF
[http://arxiv.org/pdf/1810.08770](http://arxiv.org/pdf/1810.08770)

