---
layout: post
title: "Using multi-task learning to improve the performance of acoustic-to-word and conventional hybrid models"
date: 2019-02-02 07:33:48
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Optimization Recognition
author: Thai-Son Nguyen, Sebastian Stueker, Alex Waibel
mathjax: true
---

* content
{:toc}

##### Abstract
Acoustic-to-word (A2W) models that allow direct mapping from acoustic signals to word sequences are an appealing approach to end-to-end automatic speech recognition due to their simplicity. However, prior works have shown that modelling A2W typically encounters issues of data sparsity that prevent training such a model directly. So far, pre-training initialization is the only approach proposed to deal with this issue. In this work, we propose to build a shared neural network and optimize A2W and conventional hybrid models in a multi-task manner. Our results show that training an A2W model is much more stable with our multi-task model without pre-training initialization, and results in a significant improvement compared to a baseline model. Experiments also reveal that the performance of a hybrid acoustic model can be further improved when jointly training with a sequence-level optimization criterion such as acoustic-to-word.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.01951](http://arxiv.org/abs/1902.01951)

##### PDF
[http://arxiv.org/pdf/1902.01951](http://arxiv.org/pdf/1902.01951)

