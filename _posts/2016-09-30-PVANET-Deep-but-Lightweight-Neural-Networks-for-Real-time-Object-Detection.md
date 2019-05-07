---
layout: post
title: "PVANET: Deep but Lightweight Neural Networks for Real-time Object Detection"
date: 2016-09-30 07:17:13
categories: arXiv_CV
tags: arXiv_CV Object_Detection Classification Detection
author: Kye-Hyeon Kim, Sanghoon Hong, Byungseok Roh, Yeongjae Cheon, Minje Park
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents how we can achieve the state-of-the-art accuracy in multi-category object detection task while minimizing the computational cost by adapting and combining recent technical innovations. Following the common pipeline of "CNN feature extraction + region proposal + RoI classification", we mainly redesign the feature extraction part, since region proposal part is not computationally expensive and classification part can be efficiently compressed with common techniques like truncated SVD. Our design principle is "less channels with more layers" and adoption of some building blocks including concatenated ReLU, Inception, and HyperNet. The designed network is deep and thin and trained with the help of batch normalization, residual connections, and learning rate scheduling based on plateau detection. We obtained solid results on well-known object detection benchmarks: 83.8% mAP (mean average precision) on VOC2007 and 82.5% mAP on VOC2012 (2nd place), while taking only 750ms/image on Intel i7-6700K CPU with a single core and 46ms/image on NVIDIA Titan X GPU. Theoretically, our network requires only 12.3% of the computational cost compared to ResNet-101, the winner on VOC2012.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1608.08021](https://arxiv.org/abs/1608.08021)

##### PDF
[https://arxiv.org/pdf/1608.08021](https://arxiv.org/pdf/1608.08021)

