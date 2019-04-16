---
layout: post
title: "Satellite Image Forgery Detection and Localization Using GAN and One-Class Classifier"
date: 2018-02-13 22:28:58
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Detection
author: Sri Kalyan Yarlagadda, David Güera, Paolo Bestagini, Fengqing Maggie Zhu, Stefano Tubaro, Edward J. Delp
mathjax: true
---

* content
{:toc}

##### Abstract
Current satellite imaging technology enables shooting high-resolution pictures of the ground. As any other kind of digital images, overhead pictures can also be easily forged. However, common image forensic techniques are often developed for consumer camera images, which strongly differ in their nature from satellite ones (e.g., compression schemes, post-processing, sensors, etc.). Therefore, many accurate state-of-the-art forensic algorithms are bound to fail if blindly applied to overhead image analysis. Development of novel forensic tools for satellite images is paramount to assess their authenticity and integrity. In this paper, we propose an algorithm for satellite image forgery detection and localization. Specifically, we consider the scenario in which pixels within a region of a satellite image are replaced to add or remove an object from the scene. Our algorithm works under the assumption that no forged images are available for training. Using a generative adversarial network (GAN), we learn a feature representation of pristine satellite images. A one-class support vector machine (SVM) is trained on these features to determine their distribution. Finally, image forgeries are detected as anomalies. The proposed algorithm is validated against different kinds of satellite images containing forgeries of different size and shape.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1802.04881](https://arxiv.org/abs/1802.04881)

##### PDF
[https://arxiv.org/pdf/1802.04881](https://arxiv.org/pdf/1802.04881)

