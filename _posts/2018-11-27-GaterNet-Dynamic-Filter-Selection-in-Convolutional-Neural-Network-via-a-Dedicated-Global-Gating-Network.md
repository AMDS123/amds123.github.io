---
layout: post
title: "GaterNet: Dynamic Filter Selection in Convolutional Neural Network via a Dedicated Global Gating Network"
date: 2018-11-27 19:14:49
categories: arXiv_CV
tags: arXiv_CV CNN Prediction
author: Zhourong Chen, Yang Li, Samy Bengio, Si Si
mathjax: true
---

* content
{:toc}

##### Abstract
The concept of conditional computation for deep nets has been proposed previously to improve model performance by selectively using only parts of the model conditioned on the sample it is processing. In this paper, we investigate input-dependent dynamic filter selection in deep convolutional neural networks (CNNs). The problem is interesting because the idea of forcing different parts of the model to learn from different types of samples may help us acquire better filters in CNNs, improve the model generalization performance and potentially increase the interpretability of model behavior. We propose a novel yet simple framework called GaterNet, which involves a backbone and a gater network. The backbone network is a regular CNN that performs the major computation needed for making a prediction, while a global gater network is introduced to generate binary gates for selectively activating filters in the backbone network based on each input. Extensive experiments on CIFAR and ImageNet datasets show that our models consistently outperform the original models with a large margin. On CIFAR-10, our model also improves upon state-of-the-art results.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.11205](http://arxiv.org/abs/1811.11205)

##### PDF
[http://arxiv.org/pdf/1811.11205](http://arxiv.org/pdf/1811.11205)

