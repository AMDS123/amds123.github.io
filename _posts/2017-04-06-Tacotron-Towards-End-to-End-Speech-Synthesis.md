---
layout: post
title: "Tacotron: Towards End-to-End Speech Synthesis"
date: 2017-04-06 21:20:34
categories: arXiv_SD
tags: arXiv_SD
author: Yuxuan Wang, RJ Skerry-Ryan, Daisy Stanton, Yonghui Wu, Ron J. Weiss, Navdeep Jaitly, Zongheng Yang, Ying Xiao, Zhifeng Chen, Samy Bengio, Quoc Le, Yannis Agiomyrgiannakis, Rob Clark, Rif A. Saurous
mathjax: true
---

* content
{:toc}

##### Abstract
A text-to-speech synthesis system typically consists of multiple stages, such as a text analysis frontend, an acoustic model and an audio synthesis module. Building these components often requires extensive domain expertise and may contain brittle design choices. In this paper, we present Tacotron, an end-to-end generative text-to-speech model that synthesizes speech directly from characters. Given <text, audio> pairs, the model can be trained completely from scratch with random initialization. We present several key techniques to make the sequence-to-sequence framework perform well for this challenging task. Tacotron achieves a 3.82 subjective 5-scale mean opinion score on US English, outperforming a production parametric system in terms of naturalness. In addition, since Tacotron generates speech at the frame level, it's substantially faster than sample-level autoregressive methods.

##### Abstract (translated by Google)
文本到语音合成系统通常由多个阶段组成，诸如文本分析前端，声学模型和音频合成模块。构建这些组件往往需要广泛的领域专业知识，可能包含脆弱的设计选择。在本文中，我们介绍Tacotron，一个端到端的生成文本到语音模型，直接从字符合成语音。给定<文本，音频>对，模型可以从头开始随机初始化。我们提出了几个关键的技术，使序列框架顺利执行这个具有挑战性的任务。 Tacotron的美国英语达到了3.82的主观5级平均意见分数，在自然度方面表现优于生产参数系统。另外，由于Tacotron在帧级产生语音，所以比样本级的自回归方法快得多。

##### URL
[https://arxiv.org/abs/1703.10135](https://arxiv.org/abs/1703.10135)

##### PDF
[https://arxiv.org/pdf/1703.10135](https://arxiv.org/pdf/1703.10135)

