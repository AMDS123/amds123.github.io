---
layout: post
title: "End-to-end contextual speech recognition using class language models and a token passing decoder"
date: 2018-12-05 18:00:36
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Language_Model Recognition
author: Zhehuai Chen, Mahaveer Jain, Yongqiang Wang, Michael L. Seltzer, Christian Fuegen
mathjax: true
---

* content
{:toc}

##### Abstract
End-to-end modeling (E2E) of automatic speech recognition (ASR) blends all the components of a traditional speech recognition system into a unified model. Although it simplifies training and decoding pipelines, the unified model is hard to adapt when mismatch exists between training and test data. In this work, we focus on contextual speech recognition, which is particularly challenging for E2E models because it introduces significant mismatch between training and test data. To improve the performance in the presence of complex contextual information, we propose to use class-based language models(CLM) that can populate the classes with contextdependent information in real-time. To enable this approach to scale to a large number of class members and minimize search errors, we propose a token passing decoder with efficient token recombination for E2E systems for the first time. We evaluate the proposed system on general and contextual ASR, and achieve relative 62% Word Error Rate(WER) reduction for contextual ASR without hurting performance for general ASR. We show that the proposed method performs well without modification of the decoding hyper-parameters across tasks, making it a general solution for E2E ASR.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.02142](http://arxiv.org/abs/1812.02142)

##### PDF
[http://arxiv.org/pdf/1812.02142](http://arxiv.org/pdf/1812.02142)

