---
layout: post
title: "Adversarial Examples Versus Cloud-based Detectors: A Black-box Empirical Study"
date: 2019-07-02 13:43:33
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection Segmentation Attention Semantic_Segmentation Classification Deep_Learning Detection
author: Xurong Li, Shouling Ji, Meng Han, Juntao Ji, Zhenyu Ren, Yushan Liu, Chunming Wu
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning has been broadly leveraged by major cloud providers such as Google, AWS, Baidu, to offer various computer vision related services including image auto-classification, object identification, and illegal image detection, etc. While the recent works demonstrated that the deep learning classification models are vulnerable to adversarial examples, the more complicated cloud-based image detections models also have similar security concern but not get enough attention in literature yet. In this paper, we mainly focus on the security issues of real-world cloud-based image detectors. Specifically, (1) based on effective semantic segmentation, we propose four different attacks to generate semantics-aware adversarial examples via only interacting with black-box APIs; and (2) we make the first attempt to conduct an extensive empirical study of black-box attacks against real-world cloud-based image detectors. Through the comprehensive evaluations on five major cloud platforms on AWS, Azure, Google Cloud, Baidu Cloud, and Alibaba Cloud, we demonstrate that our Image Processing attacks have a success rate of approximately 100%, and the semantic segmentation based attacks have a success rate over 90% among different detection services, such as violence, politician, and pornography detection, etc. We also proposed several possible defense strategies for these security challenges in the real-life situation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.01223](http://arxiv.org/abs/1901.01223)

##### PDF
[http://arxiv.org/pdf/1901.01223](http://arxiv.org/pdf/1901.01223)

