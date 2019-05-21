---
layout: post
title: "Semi-Supervised Learning by Augmented Distribution Alignment"
date: 2019-05-20 15:30:10
categories: arXiv_CV
tags: arXiv_CV Adversarial
author: Qin Wang, Wen Li, Luc Van Gool
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we propose a simple yet effective semi-supervised learning approach called Augmented Distribution Alignment. We reveal that an essential sampling bias exists in semi-supervised learning due to the limited amount of labeled samples, which often leads to a considerable empirical distribution mismatch between labeled data and unlabeled data. To this end, we propose to align the empirical distributions of labeled and unlabeled data to alleviate the bias. On one hand, we adopt an adversarial training strategy to minimize the distribution distance between labeled and unlabeled data as inspired by domain adaptation works. On the other hand, to deal with the small sample size issue of labeled data, we also propose a simple interpolation strategy to generate pseudo training samples. Those two strategies can be easily implemented into existing deep neural networks. We demonstrate the effectiveness of our proposed approach on the benchmark SVHN and CIFAR10 datasets, on which we achieve new state-of-the-art error rates of $3.54\%$ and $10.09\%$, respectively. Our code will be available at \url{https://github.com/qinenergy/adanet}.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.08171](http://arxiv.org/abs/1905.08171)

##### PDF
[http://arxiv.org/pdf/1905.08171](http://arxiv.org/pdf/1905.08171)

