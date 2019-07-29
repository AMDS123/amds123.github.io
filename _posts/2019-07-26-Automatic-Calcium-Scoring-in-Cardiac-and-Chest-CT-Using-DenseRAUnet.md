---
layout: post
title: "Automatic Calcium Scoring in Cardiac and Chest CT Using DenseRAUnet"
date: 2019-07-26 06:30:44
categories: arXiv_CV
tags: arXiv_CV
author: Jiechao Ma, Rongguo Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Cardiovascular disease (CVD) is a common and strong threat to human beings, featuring high prevalence, disability and mortality. The amount of coronary artery calcification (CAC) is an effective factor for CVD risk evaluation. Conventionally, CAC is quantified using ECG-synchronized cardiac CT but rarely from general chest CT scans. However, compared with ECG-synchronized cardiac CT, chest CT is more prevalent and economical in clinical practice. To address this, we propose an automatic method based on Dense U-Net to segment coronary calcium pixels on both types of CT scans. Our contribution is two-fold. First, we propose a novel network called DenseRAUnet, which takes advantage of Dense U-net, ResNet and atrous convolutions. We prove the robustness and generalizability of our model by training it exclusively on chest CT while test on both types of CT scans. Second, we design a loss function combining bootstrap with IoU function to balance foreground and background classes. DenseRAUnet is trained in a 2.5D fashion and tested on a private dataset consisting of 144 scans. Results show an F1-score of 0.75, with 0.83 accuracy of predicting cardiovascular disease risk.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.11392](http://arxiv.org/abs/1907.11392)

##### PDF
[http://arxiv.org/pdf/1907.11392](http://arxiv.org/pdf/1907.11392)

