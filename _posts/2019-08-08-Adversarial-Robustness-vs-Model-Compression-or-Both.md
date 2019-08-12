---
layout: post
title: "Adversarial Robustness vs Model Compression, or Both?"
date: 2019-08-08 19:43:19
categories: arXiv_CV
tags: arXiv_CV Adversarial Optimization
author: Shaokai Ye, Kaidi Xu, Sijia Liu, Hao Cheng, Jan-Henrik Lambrechts, Huan Zhang, Aojun Zhou, Kaisheng Ma, Yanzhi Wang, Xue Lin
mathjax: true
---

* content
{:toc}

##### Abstract
It is well known that deep neural networks (DNNs) are vulnerable to adversarial attacks, which are implemented by adding crafted perturbations onto benign examples. Min-max robust optimization based adversarial training can provide a notion of security against adversarial attacks. However, adversarial robustness requires a significantly larger capacity of the network than that for the natural training with only benign examples. This paper proposes a framework of concurrent adversarial training and weight pruning that enables model compression while still preserving the adversarial robustness and essentially tackles the dilemma of adversarial training. Furthermore, this work studies two hypotheses about weight pruning in the conventional setting and finds that weight pruning is essential for reducing the network model size in the adversarial setting, training a small model from scratch even with inherited initialization from the large model cannot achieve both adversarial robustness and high standard accuracy. Code is available at https://github.com/yeshaokai/Robustness-Aware-Pruning-ADMM.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.12561](http://arxiv.org/abs/1903.12561)

##### PDF
[http://arxiv.org/pdf/1903.12561](http://arxiv.org/pdf/1903.12561)

