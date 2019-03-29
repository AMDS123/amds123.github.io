---
layout: post
title: "A Data-driven Adversarial Examples Recognition Framework via Adversarial Feature Genome"
date: 2019-03-28 10:54:52
categories: arXiv_CV
tags: arXiv_CV Adversarial CNN Classification Recognition
author: Li Chen, Hailun Ding, Qi Li, Jiawei Zhu, Jian Peng, Haifeng Li
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks (CNNs) are easily spoofed by adversarial examples which lead to wrong classification results. Most of the defense methods focus only on how to improve the robustness of CNNs or to detect adversarial examples. They are incapable of detecting and correctly classifying adversarial examples simultaneously. We find that adversarial examples and original images have diverse representations in the feature space, and this difference grows as layers go deeper, which we call Adversarial Feature Separability (AFS). Inspired by AFS, we propose a defense framework based on Adversarial Feature Genome (AFG), which can detect and correctly classify adversarial examples into original classes simultaneously. AFG is an innovative encoding for both image and adversarial example. It consists of group features and a mixed label. With group features which are visual representations of adversarial and original images via group visualization method, one can detect adversarial examples because of ASF of group features. With a mixed label, one can trace back to the original label of an adversarial example. Then, the classification of adversarial example is modeled as a multi-label classification trained on the AFG dataset, which can get the original class of adversarial example. Experiments show that the proposed framework not only effectively detects adversarial examples from different attack algorithms, but also correctly classifies adversarial examples. Our framework potentially gives a new perspective, i.e., a data-driven way, to improve the robustness of a CNN model.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.10085](http://arxiv.org/abs/1812.10085)

##### PDF
[http://arxiv.org/pdf/1812.10085](http://arxiv.org/pdf/1812.10085)

