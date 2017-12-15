---
layout: post
title: "Fast and Accurate OOV Decoder on High-Level Features"
date: 2017-07-19 17:03:34
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Optimization Recognition
author: Yuri Khokhlov, Natalia Tomashenko, Ivan Medennikov, Alexei Romanenko
mathjax: true
---

* content
{:toc}

##### Abstract
This work proposes a novel approach to out-of-vocabulary (OOV) keyword search (KWS) task. The proposed approach is based on using high-level features from an automatic speech recognition (ASR) system, so called phoneme posterior based (PPB) features, for decoding. These features are obtained by calculating time-dependent phoneme posterior probabilities from word lattices, followed by their smoothing. For the PPB features we developed a special novel very fast, simple and efficient OOV decoder. Experimental results are presented on the Georgian language from the IARPA Babel Program, which was the test language in the OpenKWS 2016 evaluation campaign. The results show that in terms of maximum term weighted value (MTWV) metric and computational speed, for single ASR systems, the proposed approach significantly outperforms the state-of-the-art approach based on using in-vocabulary proxies for OOV keywords in the indexed database. The comparison of the two OOV KWS approaches on the fusion results of the nine different ASR systems demonstrates that the proposed OOV decoder outperforms the proxy-based approach in terms of MTWV metric given the comparable processing speed. Other important advantages of the OOV decoder include extremely low memory consumption and simplicity of its implementation and parameter optimization.

##### Abstract (translated by Google)
这项工作提出了一种新颖的词法（OOV）关键字搜索（KWS）任务的方法。所提出的方法基于使用来自自动语音识别（ASR）系统的高级特征，即所谓的基于音素后验（PPB）特征的解码。这些特征是通过计算来自单词格的随时间变化的音素后验概率，然后进行平滑来获得的。对于PPB特性，我们开发了一种特别新颖的，非常快速，简单和高效的OOV解码器。 IARPA Babel计划以OpenKWS 2016评估活动的测试语言介绍了格鲁吉亚语的实验结果。结果表明，就最大权重值（MTWV）度量和计算速度而言，对于单个ASR系统，所提出的方法明显优于基于使用用于OOV关键词的词典内代理的最新方法索引数据库。两种OOV KWS方法对九种不同ASR系统的融合结果的比较表明，所提出的OOV解码器在给定可比处理速度的情况下在MTWV度量方面优于基于代理的方法。 OOV解码器的其他重要优点包括极低的内存消耗和简单的实现和参数优化。

##### URL
[https://arxiv.org/abs/1707.06195](https://arxiv.org/abs/1707.06195)

##### PDF
[https://arxiv.org/pdf/1707.06195](https://arxiv.org/pdf/1707.06195)

