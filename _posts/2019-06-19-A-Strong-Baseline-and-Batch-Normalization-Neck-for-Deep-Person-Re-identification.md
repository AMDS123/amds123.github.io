---
layout: post
title: "A Strong Baseline and Batch Normalization Neck for Deep Person Re-identification"
date: 2019-06-19 20:12:20
categories: arXiv_CV
tags: arXiv_CV Re-identification Person_Re-identification Embedding Classification
author: Hao Luo, Wei Jiang, Youzhi Gu, Fuxu Liu, Xingyu Liao, Shenqi Lai, Jianyang Gu
mathjax: true
---

* content
{:toc}

##### Abstract
This study explores a simple but strong baseline for person re-identification (ReID). Person ReID with deep neural networks has progressed and achieved high performance in recent years. However, many state-of-the-art methods design complex network structures and concatenate multi-branch features. In the literature, some effective training tricks briefly appear in several papers or source codes. The present study collects and evaluates these effective training tricks in person ReID. By combining these tricks, the model achieves 94.5% rank-1 and 85.9% mean average precision on Market1501 with only using the global features of ResNet50. The performance surpasses all existing global- and part-based baselines in person ReID. We propose a novel neck structure named as batch normalization neck (BNNeck). BNNeck adds a batch normalization layer after global pooling layer to separate metric and classification losses into two different feature spaces because we observe they are inconsistent in one embedding space. Extended experiments show that BNNeck can boost the baseline, and our baseline can improve the performance of existing state-of-the-art methods. Our codes and models are available at: https://github.com/michuanhaohao/reid-strong-baseline.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.08332](http://arxiv.org/abs/1906.08332)

##### PDF
[http://arxiv.org/pdf/1906.08332](http://arxiv.org/pdf/1906.08332)

