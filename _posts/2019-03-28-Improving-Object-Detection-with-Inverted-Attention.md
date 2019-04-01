---
layout: post
title: "Improving Object Detection with Inverted Attention"
date: 2019-03-28 20:41:11
categories: arXiv_CV
tags: arXiv_CV Object_Detection Attention Detection
author: Zeyi Huang, Wei Ke, Dong Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Improving object detectors against occlusion, blur and noise is a critical step to deploy detectors in real applications. Since it is not possible to exhaust all image defects through data collection, many researchers seek to generate hard samples in training. The generated hard samples are either images or feature maps with coarse patches dropped out in the spatial dimensions. Significant overheads are required in training the extra hard samples and/or estimating drop-out patches using extra network branches. In this paper, we improve object detectors using a highly efficient and fine-grain mechanism called Inverted Attention (IA). Different from the original detector network that only focuses on the dominant part of objects, the detector network with IA iteratively inverts attention on feature maps and puts more attention on complementary object parts, feature channels and even context. Our approach (1) operates along both the spatial and channels dimensions of the feature maps; (2) requires no extra training on hard samples, no extra network parameters for attention estimation, and no testing overheads. Experiments show that our approach consistently improved both two-stage and single-stage detectors on benchmark databases.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.12255](http://arxiv.org/abs/1903.12255)

##### PDF
[http://arxiv.org/pdf/1903.12255](http://arxiv.org/pdf/1903.12255)

