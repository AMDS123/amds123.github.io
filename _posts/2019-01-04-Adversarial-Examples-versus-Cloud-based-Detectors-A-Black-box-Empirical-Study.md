---
layout: post
title: "Adversarial Examples versus Cloud-based Detectors: A Black-box Empirical Study"
date: 2019-01-04 17:34:13
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection Segmentation Semantic_Segmentation Classification Deep_Learning Detection
author: Xurong Li, Shouling Ji, Meng Han, Juntao Ji, Zhenyu Ren, Yushan Liu, Chunming Wu
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning has been broadly leveraged by major cloud providers such as Google, AWS, Baidu, to offer various computer vision related services including image auto-classification, object identification and illegal image detection. While many recent works demonstrated that deep learning classification models are vulnerable to adversarial examples, real-world cloud-based image detection services are more complex than classification and there is little literature about adversarial example attacks on detection services. In this paper, we mainly focus on studying the security of real-world cloud-based image detectors. Specifically, (1) based on effective semantic segmentation, we propose four different attacks to generate semantics-aware adversarial examples via only interacting with black-box APIs; and (2) we make the first attempt to conduct an extensive empirical study of black-box attacks against real-world cloud-based image detectors. Through evaluations on five popular cloud platforms including AWS, Azure, Google Cloud, Baidu Cloud and Alibaba Cloud, we demonstrate that our IP attack has a success rate of approximately 100%, and semantic segmentation based attacks (e.g., SP, SBLS, SBB) have a a success rate over 90% among different detection services, such as violence, politician and pornography detection. We discuss the possible defenses to address these security challenges in cloud-based detectors.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1901.01223](https://arxiv.org/abs/1901.01223)

##### PDF
[https://arxiv.org/pdf/1901.01223](https://arxiv.org/pdf/1901.01223)

