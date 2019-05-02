---
layout: post
title: "AdaCos: Adaptively Scaling Cosine Logits for Effectively Learning Deep Face Representations"
date: 2019-05-01 12:58:05
categories: arXiv_CV
tags: arXiv_CV Face Optimization Classification Deep_Learning Recognition Face_Recognition
author: Xiao Zhang, Rui Zhao, Yu Qiao, Xiaogang Wang, Hongsheng Li
mathjax: true
---

* content
{:toc}

##### Abstract
The cosine-based softmax losses and their variants achieve great success in deep learning based face recognition. However, hyperparameter settings in these losses have significant influences on the optimization path as well as the final recognition performance. Manually tuning those hyperparameters heavily relies on user experience and requires many training tricks. In this paper, we investigate in depth the effects of two important hyperparameters of cosine-based softmax losses, the scale parameter and angular margin parameter, by analyzing how they modulate the predicted classification probability. Based on these analysis, we propose a novel cosine-based softmax loss, AdaCos, which is hyperparameter-free and leverages an adaptive scale parameter to automatically strengthen the training supervisions during the training process. We apply the proposed AdaCos loss to large-scale face verification and identification datasets, including LFW, MegaFace, and IJB-C 1:1 Verification. Our results show that training deep neural networks with the AdaCos loss is stable and able to achieve high face recognition accuracy. Our method outperforms state-of-the-art softmax losses on all the three datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.00292](http://arxiv.org/abs/1905.00292)

##### PDF
[http://arxiv.org/pdf/1905.00292](http://arxiv.org/pdf/1905.00292)

