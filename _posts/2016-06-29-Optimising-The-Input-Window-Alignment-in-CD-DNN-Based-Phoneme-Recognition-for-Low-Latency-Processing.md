---
layout: post
title: "Optimising The Input Window Alignment in CD-DNN Based Phoneme Recognition for Low Latency Processing"
date: 2016-06-29 15:51:44
categories: arXiv_CL
tags: arXiv_CL Recognition
author: Akash Kumar Dhaka, Giampiero Salvi
mathjax: true
---

* content
{:toc}

##### Abstract
We present a systematic analysis on the performance of a phonetic recogniser when the window of input features is not symmetric with respect to the current frame. The recogniser is based on Context Dependent Deep Neural Networks (CD-DNNs) and Hidden Markov Models (HMMs). The objective is to reduce the latency of the system by reducing the number of future feature frames required to estimate the current output. Our tests performed on the TIMIT database show that the performance does not degrade when the input window is shifted up to 5 frames in the past compared to common practice (no future frame). This corresponds to improving the latency by 50 ms in our settings. Our tests also show that the best results are not obtained with the symmetric window commonly employed, but with an asymmetric window with eight past and two future context frames, although this observation should be confirmed on other data sets. The reduction in latency suggested by our results is critical for specific applications such as real-time lip synchronisation for tele-presence, but may also be beneficial in general applications to improve the lag in human-machine spoken interaction.

##### Abstract (translated by Google)
当输入特征的窗口相对于当前帧不对称时，我们对语音识别器的性能进行了系统的分析。识别器基于上下文相关的深度神经网络（CD-DNN）和隐马尔可夫模型（HMM）。目标是通过减少估计当前输出所需的未来特征帧的数量来减少系统的延迟。我们在TIMIT数据库上执行的测试显示，与常规做法（没有未来的帧）相比，当输入窗口过去移至5帧时，性能不会降低。这相当于在我们的设置中将延迟提高了50 ms。我们的测试还表明，虽然这个观察结果应该在其他数据集上得到证实，但是最好的结果并不是通常使用的对称窗口而获得的，而是具有八个过去和未来的上下文框架的不对称窗口。我们的结果所提示的等待时间的减少对于特定应用（例如远程存在的实时唇同步）是至关重要的，但是在一般应用中也可能有益于改善人机交互的滞后性。

##### URL
[https://arxiv.org/abs/1606.09163](https://arxiv.org/abs/1606.09163)

##### PDF
[https://arxiv.org/pdf/1606.09163](https://arxiv.org/pdf/1606.09163)

