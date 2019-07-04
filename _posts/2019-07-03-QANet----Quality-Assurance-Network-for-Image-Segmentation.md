---
layout: post
title: "QANet -- Quality Assurance Network for Image Segmentation"
date: 2019-07-03 08:39:52
categories: arXiv_AI
tags: arXiv_AI Adversarial QA Segmentation GAN Deep_Learning Prediction
author: Assaf Arbelle, Eliav Elul, Tammy Riklin Raviv
mathjax: true
---

* content
{:toc}

##### Abstract
Tools and methods for automatic image segmentation are rapidly developing, each with its own strengths and weaknesses. While these methods are designed to be as general as possible, there are no guarantees for their performance on new data. The choice between methods is usually based on benchmark performance whereas the data in the benchmark can be significantly different than that of the user. We introduce a novel Deep Learning method which, given an image and a proposed corresponding segmentation, obtained by any method, estimates the Intersection over Union measure (IoU) with respect to the unknown ground truth. We refer to this method as a Quality Assurance Network -- QANet. The QANet is designed to give the user an estimate of the segmentation quality on the users own, private, data without the need for human inspection or labeling. It is based on the RibCage Network architecture, originally proposed as a discriminator in an adversarial network framework. The QANet was trained on simulated data with synthesized segmentations and was tested on real cell images and segmentations obtained by three different automatic methods as submitted to the Cell Segmentation Benchmark. We show that the QANet's predictions of the IoU scores accurately estimates to the IoU scores evaluated by the benchmark organizers based on the ground truth segmentation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08503](http://arxiv.org/abs/1904.08503)

##### PDF
[http://arxiv.org/pdf/1904.08503](http://arxiv.org/pdf/1904.08503)

