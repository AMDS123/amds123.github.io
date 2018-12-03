---
layout: post
title: "Transferable Adversarial Attacks for Image and Video Object Detection"
date: 2018-11-30 06:55:22
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection GAN Detection
author: Xingxing Wei, Siyuan Liang, Xiaochun Cao, Jun Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
Adversarial examples have been demonstrated to threaten many computer vision tasks including object detection. However, the existing attacking methods for object detection have two limitations: poor transferability, which denotes that the generated adversarial examples have low success rate to attack other kinds of detection methods, and high computation cost, which means that they need more time to generate an adversarial image, and therefore are difficult to deal with the video data. To address these issues, we utilize a generative mechanism to obtain the adversarial image and video. In this way, the processing time is reduced. To enhance the transferability, we destroy the feature maps extracted from the feature network, which usually constitutes the basis of object detectors. The proposed method is based on the Generative Adversarial Network (GAN) framework, where we combine the high-level class loss and low-level feature loss to jointly train the adversarial example generator. A series of experiments conducted on PASCAL VOC and ImageNet VID datasets show that our method can efficiently generate image and video adversarial examples, and more importantly, these adversarial examples have better transferability, and thus, are able to simultaneously attack two kinds of representative object detection models: proposal based models like Faster-RCNN, and regression based models like SSD.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.12641](http://arxiv.org/abs/1811.12641)

##### PDF
[http://arxiv.org/pdf/1811.12641](http://arxiv.org/pdf/1811.12641)

