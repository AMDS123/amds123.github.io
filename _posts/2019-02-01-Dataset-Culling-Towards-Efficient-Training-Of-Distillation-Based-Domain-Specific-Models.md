---
layout: post
title: "Dataset Culling: Towards Efficient Training Of Distillation-Based Domain Specific Models"
date: 2019-02-01 04:23:32
categories: arXiv_CV
tags: arXiv_CV Object_Detection Inference Detection
author: Kentaro Yoshioka, Edward Lee, Simon Wong, Mark Horowitz
mathjax: true
---

* content
{:toc}

##### Abstract
Real-time CNN based object detection models for applications like surveillance can achieve high accuracy but require extensive computations. Recent work has shown 10 to 100x reduction in computation cost with domain-specific network settings. However, this prior work focused on inference only: if the domain network requires frequent retraining, training and retraining costs can be a significant bottleneck. To address training costs, we propose Dataset Culling: a pipeline to significantly reduce the required training dataset size for domain specific models. Dataset Culling reduces the dataset size by filtering out non-essential data for train-ing, and reducing the size of each image until detection degrades. Both of these operations use a confusion loss metric which enables us to execute the culling with minimal computation overhead. On a custom long-duration dataset, we show that Dataset Culling can reduce the training costs 47x with no accuracy loss or even with slight improvements. Codes are available: https://github.com/kentaroy47/DatasetCulling

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.00173](http://arxiv.org/abs/1902.00173)

##### PDF
[http://arxiv.org/pdf/1902.00173](http://arxiv.org/pdf/1902.00173)

