---
layout: post
title: "Fixup Initialization: Residual Learning Without Normalization"
date: 2019-01-27 05:30:11
categories: arXiv_CV
tags: arXiv_CV Regularization Image_Classification Classification
author: Hongyi Zhang, Yann N. Dauphin, Tengyu Ma
mathjax: true
---

* content
{:toc}

##### Abstract
Normalization layers are a staple in state-of-the-art deep neural network architectures. They are widely believed to stabilize training, enable higher learning rate, accelerate convergence and improve generalization, though the reason for their effectiveness is still an active research topic. In this work, we challenge the commonly-held beliefs by showing that none of the perceived benefits is unique to normalization. Specifically, we propose fixed-update initialization (Fixup), an initialization motivated by solving the exploding and vanishing gradient problem at the beginning of training via properly rescaling a standard initialization. We find training residual networks with Fixup to be as stable as training with normalization -- even for networks with 10,000 layers. Furthermore, with proper regularization, Fixup enables residual networks without normalization to achieve state-of-the-art performance in image classification and machine translation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.09321](http://arxiv.org/abs/1901.09321)

##### PDF
[http://arxiv.org/pdf/1901.09321](http://arxiv.org/pdf/1901.09321)

