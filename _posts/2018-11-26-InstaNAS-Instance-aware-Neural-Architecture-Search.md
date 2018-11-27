---
layout: post
title: "InstaNAS: Instance-aware Neural Architecture Search"
date: 2018-11-26 06:29:39
categories: arXiv_CV
tags: arXiv_CV Inference Classification Recognition
author: An-Chieh Cheng, Chieh Hubert Lin, Da-Cheng Juan, Wei Wei, Min Sun
mathjax: true
---

* content
{:toc}

##### Abstract
Neural Architecture Search (NAS) aims at finding one "single" architecture that achieves the best accuracy for a given task such as image recognition.In this paper, we study the instance-level variation,and demonstrate that instance-awareness is an important yet currently missing component of NAS. Based on this observation, we propose InstaNAS for searching toward instance-level architectures;the controller is trained to search and form a "distribution of architectures" instead of a single final architecture. Then during the inference phase, the controller selects an architecture from the distribution, tailored for each unseen image to achieve both high accuracy and short latency. The experimental results show that InstaNAS reduces the inference latency without compromising classification accuracy. On average, InstaNAS achieves 48.9% latency reduction on CIFAR-10 and 40.2% latency reduction on CIFAR-100 with respect to MobileNetV2 architecture.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1811.10201](https://arxiv.org/abs/1811.10201)

##### PDF
[https://arxiv.org/pdf/1811.10201](https://arxiv.org/pdf/1811.10201)

