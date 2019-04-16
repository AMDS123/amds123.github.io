---
layout: post
title: "Cost-effective Object Detection: Active Sample Mining with Switchable Selection Criteria"
date: 2019-01-12 03:32:19
categories: arXiv_CV
tags: arXiv_CV Object_Detection Attention Prediction Detection
author: Keze Wang, Liang Lin, Xiaopeng Yan, Ziliang Chen, Dongyu Zhang, Lei Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Though quite challenging, leveraging large-scale unlabeled or partially labeled data in learning systems (e.g., model/classifier training) has attracted increasing attentions due to its fundamental importance. To address this problem, many active learning (AL) methods have been proposed that employ up-to-date detectors to retrieve representative minority samples according to predefined confidence or uncertainty thresholds. However, these AL methods cause the detectors to ignore the remaining majority samples (i.e., those with low uncertainty or high prediction confidence). In this work, by developing a principled active sample mining (ASM) framework, we demonstrate that cost-effectively mining samples from these unlabeled majority data is key to training more powerful object detectors while minimizing user effort. Specifically, our ASM framework involves a switchable sample selection mechanism for determining whether an unlabeled sample should be manually annotated via AL or automatically pseudo-labeled via a novel self-learning process. The proposed process can be compatible with mini-batch based training (i.e., using a batch of unlabeled or partially labeled data as a one-time input) for object detection. In addition, a few samples with low-confidence predictions are selected and annotated via AL. Notably, our method is suitable for object categories that are not seen in the unlabeled data during the learning process. Extensive experiments clearly demonstrate that our ASM framework can achieve performance comparable to that of alternative methods but with significantly fewer annotations.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1807.00147](https://arxiv.org/abs/1807.00147)

##### PDF
[https://arxiv.org/pdf/1807.00147](https://arxiv.org/pdf/1807.00147)

