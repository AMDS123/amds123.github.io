---
layout: post
title: "DuTongChuan: Context-aware Translation Model for Simultaneous Interpreting"
date: 2019-07-30 14:35:06
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Recognition
author: Hao Xiong, Ruiqing Zhang, Chuanqiang Zhang, Zhongjun He, Hua Wu, Haifeng Wang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present DuTongChuan, a novel context-aware translation model for simultaneous interpreting. This model allows to constantly read streaming text from the Automatic Speech Recognition (ASR) model and simultaneously determine the boundaries of Information Units (IUs) one after another. The detected IU is then translated into a fluent translation with two simple yet effective decoding strategies: partial decoding and context-aware decoding. In practice, by controlling the granularity of IUs and the size of the context, we can get a good trade-off between latency and translation quality easily. Elaborate evaluation from human translators reveals that our system achieves promising translation quality (85.71% for Chinese-English, and 86.36% for English-Chinese), specially in the sense of surprisingly good discourse coherence. According to an End-to-End (speech-to-speech simultaneous interpreting) evaluation, this model presents impressive performance in reducing latency (to less than 3 seconds at most times). Furthermore, we successfully deploy this model in a variety of Baidu's products which have hundreds of millions of users, and we release it as a service in our AI platform.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.12984](http://arxiv.org/abs/1907.12984)

##### PDF
[http://arxiv.org/pdf/1907.12984](http://arxiv.org/pdf/1907.12984)

