---
layout: post
title: "Efficient Privacy Preserving Viola-Jones Type Object Detection via Random Base Image Representation"
date: 2017-03-30 14:06:21
categories: arXiv_CV
tags: arXiv_CV Image_Caption Object_Detection Detection
author: Xin Jin, Peng Yuan, Xiaodong Li, Chenggen Song, Shiming Ge, Geng Zhao, Yingya Chen
mathjax: true
---

* content
{:toc}

##### Abstract
A cloud server spent a lot of time, energy and money to train a Viola-Jones type object detector with high accuracy. Clients can upload their photos to the cloud server to find objects. However, the client does not want the leakage of the content of his/her photos. In the meanwhile, the cloud server is also reluctant to leak any parameters of the trained object detectors. 10 years ago, Avidan & Butman introduced Blind Vision, which is a method for securely evaluating a Viola-Jones type object detector. Blind Vision uses standard cryptographic tools and is painfully slow to compute, taking a couple of hours to scan a single image. The purpose of this work is to explore an efficient method that can speed up the process. We propose the Random Base Image (RBI) Representation. The original image is divided into random base images. Only the base images are submitted randomly to the cloud server. Thus, the content of the image can not be leaked. In the meanwhile, a random vector and the secure Millionaire protocol are leveraged to protect the parameters of the trained object detector. The RBI makes the integral-image enable again for the great acceleration. The experimental results reveal that our method can retain the detection accuracy of that of the plain vision algorithm and is significantly faster than the traditional blind vision, with only a very low probability of the information leakage theoretically.

##### Abstract (translated by Google)
云服务器花费了大量的时间，精力和金钱，以高精度训练Viola-Jones型物体探测器。客户可以将他们的照片上传到云服务器来查找对象。但是，客户不希望他/她的照片的内容泄漏。同时，云服务器也不愿意泄漏训练对象探测器的任何参数。 10年前，Avidan＆Butman推出了Blind Vision，这是一种安全评估Viola-Jones型物体探测器的方法。 Blind Vision使用标准的加密工具，计算速度很慢，需要几个小时来扫描单个图像。这项工作的目的是探索一个有效的方法，可以加快这个过程。我们提出了随机基础图像（RBI）表示。原始图像被分成随机基本图像。只有基础图像被随机提交到云服务器。因此，图像的内容不能被泄漏。同时，利用随机向量和安全百万富翁协议保护训练对象检测器的参数。 RBI使得整个图像使能重新加速。实验结果表明，该方法能够保留平视觉算法的检测精度，并且明显快于传统盲视图，理论上信息泄露的概率很低。

##### URL
[https://arxiv.org/abs/1702.08318](https://arxiv.org/abs/1702.08318)

