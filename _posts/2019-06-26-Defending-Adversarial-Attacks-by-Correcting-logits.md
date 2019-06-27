---
layout: post
title: "Defending Adversarial Attacks by Correcting logits"
date: 2019-06-26 11:07:29
categories: arXiv_CV
tags: arXiv_CV Adversarial Deep_Learning Prediction
author: Yifeng Li, Lingxi Xie, Ya Zhang, Rui Zhang, Yanfeng Wang, Qi Tian
mathjax: true
---

* content
{:toc}

##### Abstract
Generating and eliminating adversarial examples has been an intriguing topic in the field of deep learning. While previous research verified that adversarial attacks are often fragile and can be defended via image-level processing, it remains unclear how high-level features are perturbed by such attacks. We investigate this issue from a new perspective, which purely relies on logits, the class scores before softmax, to detect and defend adversarial attacks. Our defender is a two-layer network trained on a mixed set of clean and perturbed logits, with the goal being recovering the original prediction. Upon a wide range of adversarial attacks, our simple approach shows promising results with relatively high accuracy in defense, and the defender can transfer across attackers with similar properties. More importantly, our defender can work in the scenarios that image data are unavailable, and enjoys high interpretability especially at the semantic level.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.10973](http://arxiv.org/abs/1906.10973)

##### PDF
[http://arxiv.org/pdf/1906.10973](http://arxiv.org/pdf/1906.10973)

