---
layout: post
title: "Computing Valid p-values for Image Segmentation by Selective Inference"
date: 2019-06-03 08:27:27
categories: arXiv_CV
tags: arXiv_CV Segmentation Inference
author: Kosuke Tanizaki, Noriaki Hashimoto, Yu Inatsu, Hidekata Hontani, Ichiro Takeuchi
mathjax: true
---

* content
{:toc}

##### Abstract
Image segmentation is one of the most fundamental tasks of computer vision. In many practical applications, it is essential to properly evaluate the reliability of individual segmentation results. In this study, we propose a novel framework to provide the statistical significance of segmentation results in the form of p-values. Specifically, we consider a statistical hypothesis test for determining the difference between the object and the background regions. This problem is challenging because the difference can be deceptively large (called segmentation bias) due to the adaptation of the segmentation algorithm to the data. To overcome this difficulty, we introduce a statistical approach called selective inference, and develop a framework to compute valid p-values in which the segmentation bias is properly accounted for. Although the proposed framework is potentially applicable to various segmentation algorithms, we focus in this paper on graph cut-based and threshold-based segmentation algorithms, and develop two specific methods to compute valid p-values for the segmentation results obtained by these algorithms. We prove the theoretical validity of these two methods and demonstrate their practicality by applying them to segmentation problems for medical images.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.00629](http://arxiv.org/abs/1906.00629)

##### PDF
[http://arxiv.org/pdf/1906.00629](http://arxiv.org/pdf/1906.00629)

