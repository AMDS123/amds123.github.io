---
layout: post
title: "A Highly Efficient Distributed Deep Learning System For Automatic Speech Recognition"
date: 2019-07-10 14:32:59
categories: arXiv_SD
tags: arXiv_SD Knowledge Speech_Recognition Deep_Learning Gradient_Descent Recognition
author: Wei Zhang, Xiaodong Cui, Ulrich Finkler, George Saon, Abdullah Kayi, Alper Buyuktosunoglu, Brian Kingsbury, David Kung, Michael Picheny
mathjax: true
---

* content
{:toc}

##### Abstract
Modern Automatic Speech Recognition (ASR) systems rely on distributed deep learning to for quick training completion. To enable efficient distributed training, it is imperative that the training algorithms can converge with a large mini-batch size. In this work, we discovered that Asynchronous Decentralized Parallel Stochastic Gradient Descent (ADPSGD) can work with much larger batch size than commonly used Synchronous SGD (SSGD) algorithm. On commonly used public SWB-300 and SWB-2000 ASR datasets, ADPSGD can converge with a batch size 3X as large as the one used in SSGD, thus enable training at a much larger scale. Further, we proposed a Hierarchical-ADPSGD (H-ADPSGD) system in which learners on the same computing node construct a super learner via a fast allreduce implementation, and super learners deploy ADPSGD algorithm among themselves. On a 64 Nvidia V100 GPU cluster connected via a 100Gb/s Ethernet network, our system is able to train SWB-2000 to reach a 7.6% WER on the Hub5-2000 Switchboard (SWB) test-set and a 13.2% WER on the Call-home (CH) test-set in 5.2 hours. To the best of our knowledge, this is the fastest ASR training system that attains this level of model accuracy for SWB-2000 task to be ever reported in the literature.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.05701](http://arxiv.org/abs/1907.05701)

##### PDF
[http://arxiv.org/pdf/1907.05701](http://arxiv.org/pdf/1907.05701)

