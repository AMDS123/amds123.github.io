---
layout: post
title: "K for the Price of 1: Parameter-efficient Multi-task and Transfer Learning"
date: 2019-02-24 02:03:00
categories: arXiv_CV
tags: arXiv_CV Image_Classification Transfer_Learning Classification Detection
author: Pramod Kaushik Mudrakarta, Mark Sandler, Andrey Zhmoginov, Andrew Howard
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a novel method that enables parameter-efficient transfer and multi-task learning with deep neural networks. The basic approach is to learn a model patch - a small set of parameters - that will specialize to each task, instead of fine-tuning the last layer or the entire network. For instance, we show that learning a set of scales and biases is sufficient to convert a pretrained network to perform well on qualitatively different problems (e.g. converting a Single Shot MultiBox Detection (SSD) model into a 1000-class image classification model while reusing 98% of parameters of the SSD feature extractor). Similarly, we show that re-learning existing low-parameter layers (such as depth-wise convolutions) while keeping the rest of the network frozen also improves transfer-learning accuracy significantly. Our approach allows both simultaneous (multi-task) as well as sequential transfer learning. In several multi-task learning problems, despite using much fewer parameters than traditional logits-only fine-tuning, we match single-task performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.10703](http://arxiv.org/abs/1810.10703)

##### PDF
[http://arxiv.org/pdf/1810.10703](http://arxiv.org/pdf/1810.10703)

