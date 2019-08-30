---
layout: post
title: "Two-Pass End-to-End Speech Recognition"
date: 2019-08-29 00:18:05
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition RNN Recognition
author: Tara N. Sainath, Ruoming Pang, David Rybach, Yanzhang He, Rohit Prabhavalkar, Wei Li, Mirk&#xf3; Visontai, Qiao Liang, Trevor Strohman, Yonghui Wu, Ian McGraw, Chung-Cheng Chiu
mathjax: true
---

* content
{:toc}

##### Abstract
The requirements for many applications of state-of-the-art speech recognition systems include not only low word error rate (WER) but also low latency. Specifically, for many use-cases, the system must be able to decode utterances in a streaming fashion and faster than real-time. Recently, a streaming recurrent neural network transducer (RNN-T) end-to-end (E2E) model has shown to be a good candidate for on-device speech recognition, with improved WER and latency metrics compared to conventional on-device models [1]. However, this model still lags behind a large state-of-the-art conventional model in quality [2]. On the other hand, a non-streaming E2E Listen, Attend and Spell (LAS) model has shown comparable quality to large conventional models [3]. This work aims to bring the quality of an E2E streaming model closer to that of a conventional system by incorporating a LAS network as a second-pass component, while still abiding by latency constraints. Our proposed two-pass model achieves a 17%-22% relative reduction in WER compared to RNN-T alone and increases latency by a small fraction over RNN-T.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.10992](http://arxiv.org/abs/1908.10992)

##### PDF
[http://arxiv.org/pdf/1908.10992](http://arxiv.org/pdf/1908.10992)

