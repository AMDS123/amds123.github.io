---
layout: post
title: "An online sequence-to-sequence model for noisy speech recognition"
date: 2017-06-16 20:58:43
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Inference Deep_Learning Recognition
author: Chung-Cheng Chiu, Dieterich Lawson, Yuping Luo, George Tucker, Kevin Swersky, Ilya Sutskever, Navdeep Jaitly
mathjax: true
---

* content
{:toc}

##### Abstract
Generative models have long been the dominant approach for speech recognition. The success of these models however relies on the use of sophisticated recipes and complicated machinery that is not easily accessible to non-practitioners. Recent innovations in Deep Learning have given rise to an alternative - discriminative models called Sequence-to-Sequence models, that can almost match the accuracy of state of the art generative models. While these models are easy to train as they can be trained end-to-end in a single step, they have a practical limitation that they can only be used for offline recognition. This is because the models require that the entirety of the input sequence be available at the beginning of inference, an assumption that is not valid for instantaneous speech recognition. To address this problem, online sequence-to-sequence models were recently introduced. These models are able to start producing outputs as data arrives, and the model feels confident enough to output partial transcripts. These models, like sequence-to-sequence are causal - the output produced by the model until any time, $t$, affects the features that are computed subsequently. This makes the model inherently more powerful than generative models that are unable to change features that are computed from the data. This paper highlights two main contributions - an improvement to online sequence-to-sequence model training, and its application to noisy settings with mixed speech from two speakers.

##### Abstract (translated by Google)
生成模型一直是语音识别的主要方法。然而，这些模型的成功依赖于使用复杂的配方和复杂的机械，非实践者不容易获得。深度学习方面的最新创新产生了一种称为序列 - 序列（Sequence-to-Sequence）模型的替代模型，它可以与现有技术生成模型的精度几乎匹配。虽然这些模型很容易培训，因为它们可以一步到位地进行端对端培训，但是它们具有实际限制，只能用于离线识别。这是因为模型要求在推断开始时整个输入序列是可用的，这个假设对于瞬时语音识别是无效的。为了解决这个问题，最近引入了在线序列 - 序列模型。这些模型能够在数据到达时开始产生输出，并且模型对输出部分转录本有足够的信心。这些模型，如序列到序列是因果的 - 模型产生的输出直到任何时候，$ t $都会影响随后计算的特征。这使得模型本身比不能改变从数据计算的特征的生成模型更强大。本文重点介绍了两个主要的贡献 - 对在线序列 - 序列模型训练的改进，以及将其应用于来自两个说话者的混合语音的噪声设置。

##### URL
[https://arxiv.org/abs/1706.06428](https://arxiv.org/abs/1706.06428)

##### PDF
[https://arxiv.org/pdf/1706.06428](https://arxiv.org/pdf/1706.06428)

