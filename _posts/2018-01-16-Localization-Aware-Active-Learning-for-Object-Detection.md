---
layout: post
title: "Localization-Aware Active Learning for Object Detection"
date: 2018-01-16 05:43:53
categories: arXiv_CV
tags: arXiv_CV Object_Detection Image_Classification Classification Prediction Detection
author: Chieh-Chi Kao, Teng-Yok Lee, Pradeep Sen, Ming-Yu Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Active learning - a class of algorithms that iteratively searches for the most informative samples to include in a training dataset - has been shown to be effective at annotating data for image classification. However, the use of active learning for object detection is still largely unexplored as determining informativeness of an object-location hypothesis is more difficult. In this paper, we address this issue and present two metrics for measuring the informativeness of an object hypothesis, which allow us to leverage active learning to reduce the amount of annotated data needed to achieve a target object detection performance. Our first metric measures 'localization tightness' of an object hypothesis, which is based on the overlapping ratio between the region proposal and the final prediction. Our second metric measures 'localization stability' of an object hypothesis, which is based on the variation of predicted object locations when input images are corrupted by noise. Our experimental results show that by augmenting a conventional active-learning algorithm designed for classification with the proposed metrics, the amount of labeled training data required can be reduced up to 25%. Moreover, on PASCAL 2007 and 2012 datasets our localization-stability method has an average relative improvement of 96.5% and 81.9% over the baseline method using classification only.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1801.05124](https://arxiv.org/abs/1801.05124)

##### PDF
[https://arxiv.org/pdf/1801.05124](https://arxiv.org/pdf/1801.05124)

