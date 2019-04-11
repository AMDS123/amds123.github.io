---
layout: post
title: "Distributed Deep Learning Strategies For Automatic Speech Recognition"
date: 2019-04-10 01:00:26
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition RNN Deep_Learning Recognition
author: Wei Zhang, Xiaodong Cui, Ulrich Finkler, Brian Kingsbury, George Saon, David Kung, Michael Picheny
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose and investigate a variety of distributed deep learning strategies for automatic speech recognition (ASR) and evaluate them with a state-of-the-art Long short-term memory (LSTM) acoustic model on the 2000-hour Switchboard (SWB2000), which is one of the most widely used datasets for ASR performance benchmark. We first investigate what are the proper hyper-parameters (e.g., learning rate) to enable the training with sufficiently large batch size without impairing the model accuracy. We then implement various distributed strategies, including Synchronous (SYNC), Asynchronous Decentralized Parallel SGD (ADPSGD) and the hybrid of the two HYBRID, to study their runtime/accuracy trade-off. We show that we can train the LSTM model using ADPSGD in 14 hours with 16 NVIDIA P100 GPUs to reach a 7.6% WER on the Hub5- 2000 Switchboard (SWB) test set and a 13.1% WER on the CallHome (CH) test set. Furthermore, we can train the model using HYBRID in 11.5 hours with 32 NVIDIA V100 GPUs without loss in accuracy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.04956](http://arxiv.org/abs/1904.04956)

##### PDF
[http://arxiv.org/pdf/1904.04956](http://arxiv.org/pdf/1904.04956)

