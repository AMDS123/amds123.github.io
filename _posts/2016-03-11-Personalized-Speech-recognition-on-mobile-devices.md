---
layout: post
title: "Personalized Speech recognition on mobile devices"
date: 2016-03-11 22:25:39
categories: arXiv_SD
tags: arXiv_SD Speech_Recognition RNN Classification Language_Model Recognition
author: Ian McGraw, Rohit Prabhavalkar, Raziel Alvarez, Montse Gonzalez Arenas, Kanishka Rao, David Rybach, Ouais Alsharif, Hasim Sak, Alexander Gruenstein, Francoise Beaufays, Carolina Parada
mathjax: true
---

* content
{:toc}

##### Abstract
We describe a large vocabulary speech recognition system that is accurate, has low latency, and yet has a small enough memory and computational footprint to run faster than real-time on a Nexus 5 Android smartphone. We employ a quantized Long Short-Term Memory (LSTM) acoustic model trained with connectionist temporal classification (CTC) to directly predict phoneme targets, and further reduce its memory footprint using an SVD-based compression scheme. Additionally, we minimize our memory footprint by using a single language model for both dictation and voice command domains, constructed using Bayesian interpolation. Finally, in order to properly handle device-specific information, such as proper names and other context-dependent information, we inject vocabulary items into the decoder graph and bias the language model on-the-fly. Our system achieves 13.5% word error rate on an open-ended dictation task, running with a median speed that is seven times faster than real-time.

##### Abstract (translated by Google)
我们描述了一个大型的词汇语音识别系统，它精确，延迟低，而且具有足够小的内存和计算空间，可以在Nexus 5 Android智能手机上以比实时更快的速度运行。我们使用连接主义时间分类（CTC）训练的量化长时间短时记忆（LSTM）声学模型来直接预测音素目标，并且使用基于SVD的压缩方案进一步减少其内存占用。此外，我们通过使用贝叶斯插值构造的听写命令和语音命令域的单一语言模型来最小化我们的存储器占用空间。最后，为了正确处理特定于设备的信息，例如专有名称和其他与上下文相关的信息，我们将词汇项插入到解码器图中，并对语言模型进行实时偏好。我们的系统在开放式听写任务上实现了13.5％的字错误率，以比实时速度快七倍的中间速度运行。

##### URL
[https://arxiv.org/abs/1603.03185](https://arxiv.org/abs/1603.03185)

##### PDF
[https://arxiv.org/pdf/1603.03185](https://arxiv.org/pdf/1603.03185)

