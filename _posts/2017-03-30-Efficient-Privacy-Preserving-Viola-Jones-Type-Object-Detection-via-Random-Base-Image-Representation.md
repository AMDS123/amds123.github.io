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


##### URL
[https://arxiv.org/abs/1702.08318](https://arxiv.org/abs/1702.08318)

##### PDF
[https://arxiv.org/pdf/1702.08318](https://arxiv.org/pdf/1702.08318)

