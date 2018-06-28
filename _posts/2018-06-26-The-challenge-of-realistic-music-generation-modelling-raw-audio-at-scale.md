---
layout: post
title: "The challenge of realistic music generation: modelling raw audio at scale"
date: 2018-06-26 16:48:59
categories: arXiv_SD
tags: arXiv_SD Relation
author: Sander Dieleman, A&#xe4;ron van den Oord, Karen Simonyan
mathjax: true
---

* content
{:toc}

##### Abstract
Realistic music generation is a challenging task. When building generative models of music that are learnt from data, typically high-level representations such as scores or MIDI are used that abstract away the idiosyncrasies of a particular performance. But these nuances are very important for our perception of musicality and realism, so in this work we embark on modelling music in the raw audio domain. It has been shown that autoregressive models excel at generating raw audio waveforms of speech, but when applied to music, we find them biased towards capturing local signal structure at the expense of modelling long-range correlations. This is problematic because music exhibits structure at many different timescales. In this work, we explore autoregressive discrete autoencoders (ADAs) as a means to enable autoregressive models to capture long-range correlations in waveforms. We find that they allow us to unconditionally generate piano music directly in the raw audio domain, which shows stylistic consistency across tens of seconds.

##### Abstract (translated by Google)
逼真的音乐生成是一项艰巨的任务。在构建从数据中学习的音乐的生成模型时，通常会使用高级表示法（例如乐谱或MIDI）来抽象化特定演奏的特质。但是，这些细微差别对于我们对音乐性和现实主义的感知非常重要，所以在这项工作中，我们开始在原始音频领域对音乐进行建模。已经表明，自回归模型在生成语音的原始音频波形方面非常出色，但是当应用于音乐时，我们发现它们偏向于捕获本地信号结构，造成远程相关性建模的代价。这是有问题的，因为音乐在许多不同时间尺度展示结构。在这项工作中，我们探索自回归离散自编码器（ADAs）作为一种手段，使自回归模型能够捕获波形中的长程相关性。我们发现，它们允许我们直接在原始音频域中直接生成钢琴音乐，从而在几十秒内显示文体一致性。

##### URL
[http://arxiv.org/abs/1806.10474](http://arxiv.org/abs/1806.10474)

##### PDF
[http://arxiv.org/pdf/1806.10474](http://arxiv.org/pdf/1806.10474)

