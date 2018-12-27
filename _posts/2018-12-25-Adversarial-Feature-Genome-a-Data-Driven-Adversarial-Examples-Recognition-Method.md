---
layout: post
title: "Adversarial Feature Genome: a Data Driven Adversarial Examples Recognition Method"
date: 2018-12-25 10:31:36
categories: arXiv_CV
tags: arXiv_CV Adversarial CNN Classification Prediction Quantitative Recognition
author: Li Chen, Hailun Ding, Qi Li, Jiawei Zhu, Haozhe Huang, Yifan Chang, Haifeng Li
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks (CNNs) are easily spoofed by adversarial examples which lead to wrong classification result. Most of the one-way defense methods focus only on how to improve the robustness of a CNN or to identify adversarial examples. They are incapable of identifying and correctly classifying adversarial examples simultaneously due to the lack of an effective way to quantitatively represent changes in the characteristics of the sample within the network. We find that adversarial examples and original ones have diverse representation in the feature space. Moreover, this difference grows as layers go deeper, which we call Adversarial Feature Separability (AFS). Inspired by AFS, we propose an Adversarial Feature Genome (AFG) based adversarial examples defense framework which can detect adversarial examples and correctly classify them into original category simultaneously. First, we extract the representations of adversarial examples and original ones with labels by the group visualization method. Then, we encode the representations into the feature database AFG. Finally, we model adversarial examples recognition as a multi-label classification or prediction problem by training a CNN for recognizing adversarial examples and original examples on the AFG. Experiments show that the proposed framework can not only effectively identify the adversarial examples in the defense process, but also correctly classify adversarial examples with mean accuracy up to 63\%. Our framework potentially gives a new perspective, i.e. data-driven way, to adversarial examples defense. We believe that adversarial examples defense research may benefit from a large scale AFG database which is similar to ImageNet. The database and source code can be visited at https://github.com/lehaifeng/Adversarial_Feature_Genome.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.10085](http://arxiv.org/abs/1812.10085)

##### PDF
[http://arxiv.org/pdf/1812.10085](http://arxiv.org/pdf/1812.10085)

