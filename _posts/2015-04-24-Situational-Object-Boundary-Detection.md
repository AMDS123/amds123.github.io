---
layout: post
title: "Situational Object Boundary Detection"
date: 2015-04-24 09:15:33
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Classification Detection
author: Jasper Uijlings, Vittorio Ferrari
mathjax: true
---

* content
{:toc}

##### Abstract
Intuitively, the appearance of true object boundaries varies from image to image. Hence the usual monolithic approach of training a single boundary predictor and applying it to all images regardless of their content is bound to be suboptimal. In this paper we therefore propose situational object boundary detection: We first define a variety of situations and train a specialized object boundary detector for each of them using [Dollar and Zitnick 2013]. Then given a test image, we classify it into these situations using its context, which we model by global image appearance. We apply the corresponding situational object boundary detectors, and fuse them based on the classification probabilities. In experiments on ImageNet, Microsoft COCO, and Pascal VOC 2012 segmentation we show that our situational object boundary detection gives significant improvements over a monolithic approach. Additionally, our method substantially outperforms [Hariharan et al. 2011] on semantic contour detection on their SBD dataset.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1504.06434](https://arxiv.org/abs/1504.06434)

##### PDF
[https://arxiv.org/pdf/1504.06434](https://arxiv.org/pdf/1504.06434)

