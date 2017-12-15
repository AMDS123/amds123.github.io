---
layout: post
title: "Batch-normalized joint training for DNN-based distant speech recognition"
date: 2017-03-24 15:40:19
categories: arXiv_SD
tags: arXiv_SD Face Speech_Recognition Optimization Recognition
author: Mirco Ravanelli, Philemon Brakel, Maurizio Omologo, Yoshua Bengio
mathjax: true
---

* content
{:toc}

##### Abstract
Improving distant speech recognition is a crucial step towards flexible human-machine interfaces. Current technology, however, still exhibits a lack of robustness, especially when adverse acoustic conditions are met. Despite the significant progress made in the last years on both speech enhancement and speech recognition, one potential limitation of state-of-the-art technology lies in composing modules that are not well matched because they are not trained jointly. To address this concern, a promising approach consists in concatenating a speech enhancement and a speech recognition deep neural network and to jointly update their parameters as if they were within a single bigger network. Unfortunately, joint training can be difficult because the output distribution of the speech enhancement system may change substantially during the optimization procedure. The speech recognition module would have to deal with an input distribution that is non-stationary and unnormalized. To mitigate this issue, we propose a joint training approach based on a fully batch-normalized architecture. Experiments, conducted using different datasets, tasks and acoustic conditions, revealed that the proposed framework significantly overtakes other competitive solutions, especially in challenging environments.

##### Abstract (translated by Google)
改善远距离语音识别是实现灵活人机界面的关键一步。然而，目前的技术仍然缺乏稳健性，特别是当不利的声学条件得到满足时。尽管近年来在语音增强和语音识别方面取得了重大进展，但是最先进的技术的一个潜在局限在于组合不匹配的模块，因为它们没有被共同训练。为了解决这个问题，一个有前途的方法是将语音增强和语音识别深层神经网络连接起来，并且联合更新它们的参数，就好像它们在一个更大的网络中一样。不幸的是，联合训练可能是困难的，因为在优化过程中语音增强系统的输出分布可能发生显着变化。语音识别模块将不得不处理非平稳和非标准化的输入分布。为了缓解这个问题，我们提出了一个基于完全批量规范化架构的联合培训方法。使用不同的数据集，任务和声学条件进行的实验表明，所提出的框架显着地超越了其他竞争性解决方案，特别是在具有挑战性的环境中。

##### URL
[https://arxiv.org/abs/1703.08471](https://arxiv.org/abs/1703.08471)

##### PDF
[https://arxiv.org/pdf/1703.08471](https://arxiv.org/pdf/1703.08471)

