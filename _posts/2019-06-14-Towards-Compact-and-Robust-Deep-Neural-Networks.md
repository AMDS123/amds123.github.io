---
layout: post
title: "Towards Compact and Robust Deep Neural Networks"
date: 2019-06-14 10:12:02
categories: arXiv_CV
tags: arXiv_CV Adversarial
author: Vikash Sehwag, Shiqi Wang, Prateek Mittal, Suman Jana
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks have achieved impressive performance in many applications but their large number of parameters lead to significant computational and storage overheads. Several recent works attempt to mitigate these overheads by designing compact networks using pruning of connections. However, we observe that most of the existing strategies to design compact networks fail to preserve network robustness against adversarial examples. In this work, we rigorously study the extension of network pruning strategies to preserve both benign accuracy and robustness of a network. Starting with a formal definition of the pruning procedure, including pre-training, weights pruning, and fine-tuning, we propose a new pruning method that can create compact networks while preserving both benign accuracy and robustness. Our method is based on two main insights: (1) we ensure that the training objectives of the pre-training and fine-tuning steps match the training objective of the desired robust model (e.g., adversarial robustness/verifiable robustness), and (2) we keep the pruning strategy agnostic to pre-training and fine-tuning objectives. We evaluate our method on four different networks on the CIFAR-10 dataset and measure benign accuracy, empirical robust accuracy, and verifiable robust accuracy. We demonstrate that our pruning method can preserve on average 93\% benign accuracy, 92.5\% empirical robust accuracy, and 85.0\% verifiable robust accuracy while compressing the tested network by 10$\times$.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1906.06110](https://arxiv.org/abs/1906.06110)

##### PDF
[https://arxiv.org/pdf/1906.06110](https://arxiv.org/pdf/1906.06110)

