---
layout: post
title: "Attentive Adversarial Learning for Domain-Invariant Training"
date: 2019-04-28 23:44:29
categories: arXiv_CV
tags: arXiv_CV Adversarial Attention Speech_Recognition Classification Recognition
author: Zhong Meng, Jinyu Li, Yifan Gong
mathjax: true
---

* content
{:toc}

##### Abstract
Adversarial domain-invariant training (ADIT) proves to be effective in suppressing the effects of domain variability in acoustic modeling and has led to improved performance in automatic speech recognition (ASR). In ADIT, an auxiliary domain classifier takes in equally-weighted deep features from a deep neural network (DNN) acoustic model and is trained to improve their domain-invariance by optimizing an adversarial loss function. In this work, we propose an attentive ADIT (AADIT) in which we advance the domain classifier with an attention mechanism to automatically weight the input deep features according to their importance in domain classification. With this attentive re-weighting, AADIT can focus on the domain normalization of phonetic components that are more susceptible to domain variability and generates deep features with improved domain-invariance and senone-discriminativity over ADIT. Most importantly, the attention block serves only as an external component to the DNN acoustic model and is not involved in ASR, so AADIT can be used to improve the acoustic modeling with any DNN architectures. More generally, the same methodology can improve any adversarial learning system with an auxiliary discriminator. Evaluated on CHiME-3 dataset, the AADIT achieves 13.6% and 9.3% relative WER improvements, respectively, over a multi-conditional model and a strong ADIT baseline.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.12400](http://arxiv.org/abs/1904.12400)

##### PDF
[http://arxiv.org/pdf/1904.12400](http://arxiv.org/pdf/1904.12400)

