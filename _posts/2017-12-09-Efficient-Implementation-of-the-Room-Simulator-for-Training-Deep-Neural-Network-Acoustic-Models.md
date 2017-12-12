---
layout: post
title: "Efficient Implementation of the Room Simulator for Training Deep Neural Network Acoustic Models"
date: 2017-12-09 20:58:39
categories: arXiv_SD
tags: arXiv_SD Speech_Recognition Recognition
author: Chanwoo Kim, Ehsan Variani, Arun Narayanan, Michiel Bacchiani
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we describe how to efficiently implement an acoustic room simulator to generate large-scale simulated data for training deep neural networks. Even though Google Room Simulator in [1] was shown to be quite effective in reducing the Word Error Rates (WERs) for far-field applications by generating simulated far-field training sets, it requires a very large number of Fast Fourier Transforms (FFTs) of large size. Room Simulator in [1] used approximately 80 percent of Central Processing Unit (CPU) usage in our CPU + Graphics Processing Unit (GPU) training architecture [2]. In this work, we implement an efficient OverLap Addition (OLA) based filtering using the open-source FFTW3 library. Further, we investigate the effects of the Room Impulse Response (RIR) lengths. Experimentally, we conclude that we can cut the tail portions of RIRs whose power is less than 20 dB below the maximum power without sacrificing the speech recognition accuracy. However, we observe that cutting RIR tail more than this threshold harms the speech recognition accuracy for rerecorded test sets. Using these approaches, we were able to reduce CPU usage for the room simulator portion down to 9.69 percent in CPU/GPU training architecture. Profiling result shows that we obtain 22.4 times speed-up on a single machine and 37.3 times speed up on Google's distributed training infrastructure.

##### Abstract (translated by Google)
在本文中，我们描述了如何有效地实现声学模拟器来生成训练深度神经网络的大规模模拟数据。尽管[1]中的Google房间模拟器被证明在通过生成模拟远场训练集来降低远场应用的误码率（WER）方面非常有效，但它需要大量的快速傅里叶变换（FFT） ）的大尺寸。 [1]中的Room Simulator在我们的CPU +图形处理单元（GPU）培训体系结构[2]中使用了约80％的中央处理单元（CPU）。在这项工作中，我们使用开源的FFTW3库实现了一个高效的OverLap加法（OLA）过滤。此外，我们调查房间冲动响应（RIR）长度的影响。在实验中，我们得出这样的结论：我们可以削减功率低于最大功率20 dB的RIR的尾部，而不牺牲语音识别的准确性。然而，我们观察到，削减RIR尾巴超过这个阈值有损重新记录的测试集的语音识别的准确性。使用这些方法，我们能够将CPU模拟器部分的CPU使用率降低到CPU / GPU培训架构的9.69％。剖析结果显示，我们在单机上获得了22.4倍的加速，在Google的分布式培训基础架构上获得了37.3倍的加速。

##### URL
[http://arxiv.org/abs/1712.03439](http://arxiv.org/abs/1712.03439)

##### PDF
[http://arxiv.org/pdf/1712.03439](http://arxiv.org/pdf/1712.03439)

