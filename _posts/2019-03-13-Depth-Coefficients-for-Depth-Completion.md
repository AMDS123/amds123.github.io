---
layout: post
title: "Depth Coefficients for Depth Completion"
date: 2019-03-13 11:39:00
categories: arXiv_CV
tags: arXiv_CV Object_Detection Sparse Quantitative Detection
author: Saif Imran, Yunfei Long, Xiaoming Liu, Daniel Morris
mathjax: true
---

* content
{:toc}

##### Abstract
Depth completion involves estimating a dense depth image from sparse depth measurements, often guided by a color image. While linear upsampling is straight forward, it results in artifacts including depth pixels being interpolated in empty space across discontinuities between objects. Current methods use deep networks to upsample and "complete" the missing depth pixels. Nevertheless, depth smearing between objects remains a challenge. We propose a new representation for depth called Depth Coefficients (DC) to address this problem. It enables convolutions to more easily avoid inter-object depth mixing. We also show that the standard Mean Squared Error (MSE) loss function can promote depth mixing, and thus propose instead to use cross-entropy loss for DC. With quantitative and qualitative evaluation on benchmarks, we show that switching out sparse depth input and MSE loss with our DC representation and cross-entropy loss is a simple way to improve depth completion performance, and reduce pixel depth mixing, which leads to improved depth-based object detection.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.05421](http://arxiv.org/abs/1903.05421)

##### PDF
[http://arxiv.org/pdf/1903.05421](http://arxiv.org/pdf/1903.05421)

