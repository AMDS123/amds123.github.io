---
layout: post
title: "EvalNorm: Estimating Batch Normalization Statistics for Evaluation"
date: 2019-04-12 04:54:56
categories: arXiv_CV
tags: arXiv_CV Object_Detection Deep_Learning Detection
author: Saurabh Singh, Abhinav Shrivastava
mathjax: true
---

* content
{:toc}

##### Abstract
Batch normalization (BN) has been very effective for deep learning and is widely used. However, when training with small minibatches, models using BN exhibit a significant degradation in performance. In this paper we study this peculiar behavior of BN to gain a better understanding of the problem, and identify a potential cause based on a statistical insight. We propose `EvalNorm' to address the issue by estimating corrected normalization statistics to use for BN during evaluation. EvalNorm supports online estimation of the corrected statistics while the model is being trained, and it does not affect the training scheme of the model. As a result, an added advantage of EvalNorm is that it can be used with existing pre-trained models allowing them to benefit from our method. EvalNorm yields large gains for models trained with smaller batches. Our experiments show that EvalNorm performs 6.18% (absolute) better than vanilla BN for a batchsize of 2 on ImageNet validation set and from 1.5 to 7.0 points (absolute) gain on the COCO object detection benchmark across a variety of setups.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.06031](http://arxiv.org/abs/1904.06031)

##### PDF
[http://arxiv.org/pdf/1904.06031](http://arxiv.org/pdf/1904.06031)

