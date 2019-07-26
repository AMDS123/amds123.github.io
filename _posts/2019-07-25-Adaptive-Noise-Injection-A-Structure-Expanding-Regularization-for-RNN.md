---
layout: post
title: "Adaptive Noise Injection: A Structure-Expanding Regularization for RNN"
date: 2019-07-25 07:58:08
categories: arXiv_CL
tags: arXiv_CL Regularization RNN Language_Model
author: Rui Li, Kai Shuang, Mengyu Gu, Sen Su
mathjax: true
---

* content
{:toc}

##### Abstract
The vanilla LSTM has become one of the most potential architectures in word-level language modeling, like other recurrent neural networks, overfitting is always a key barrier for its effectiveness. The existing noise-injected regularizations introduce the random noises of fixation intensity, which inhibits the learning of the RNN throughout the training process. In this paper, we propose a new structure-expanding regularization method called Adjective Noise Injection (ANI), which considers the output of an extra RNN branch as a kind of adaptive noises and injects it into the main-branch RNN output. Due to the adaptive noises can be improved as the training processes, its negative effects can be weakened and even transformed into a positive effect to further improve the expressiveness of the main-branch RNN. As a result, ANI can regularize the RNN in the early stage of training and further promoting its training performance in the later stage. We conduct experiments on three widely-used corpora: PTB, WT2, and WT103, whose results verify both the regularization and promoting the training performance functions of ANI. Furthermore, we design a series simulation experiments to explore the reasons that may lead to the regularization effect of ANI, and we find that in training process, the robustness against the parameter update errors can be strengthened when the LSTM equipped with ANI.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.10885](http://arxiv.org/abs/1907.10885)

##### PDF
[http://arxiv.org/pdf/1907.10885](http://arxiv.org/pdf/1907.10885)

