---
layout: post
title: "Self-Supervised Learning for Cardiac MR Image Segmentation by Anatomical Position Prediction"
date: 2019-07-05 10:27:38
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention CNN Classification Prediction
author: Wenjia Bai, Chen Chen, Giacomo Tarroni, Jinming Duan, Florian Guitton, Steffen E. Petersen, Yike Guo, Paul M. Matthews, Daniel Rueckert
mathjax: true
---

* content
{:toc}

##### Abstract
In the recent years, convolutional neural networks have transformed the field of medical image analysis due to their capacity to learn discriminative image features for a variety of classification and regression tasks. However, successfully learning these features requires a large amount of manually annotated data, which is expensive to acquire and limited by the available resources of expert image analysts. Therefore, unsupervised, weakly-supervised and self-supervised feature learning techniques receive a lot of attention, which aim to utilise the vast amount of available data, while at the same time avoid or substantially reduce the effort of manual annotation. In this paper, we propose a novel way for training a cardiac MR image segmentation network, in which features are learnt in a self-supervised manner by predicting anatomical positions. The anatomical positions serve as a supervisory signal and do not require extra manual annotation. We demonstrate that this seemingly simple task provides a strong signal for feature learning and with self-supervised learning, we achieve a high segmentation accuracy that is better than or comparable to a U-net trained from scratch, especially at a small data setting. When only five annotated subjects are available, the proposed method improves the mean Dice metric from 0.811 to 0.852 for short-axis image segmentation, compared to the baseline U-net.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.02757](http://arxiv.org/abs/1907.02757)

##### PDF
[http://arxiv.org/pdf/1907.02757](http://arxiv.org/pdf/1907.02757)

