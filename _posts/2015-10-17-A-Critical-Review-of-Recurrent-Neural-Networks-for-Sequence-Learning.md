---
layout: post
title: 'A Critical Review of Recurrent Neural Networks for Sequence Learning'
date: 2015-10-17 05:06:11
categories: arXiv_CV
tags: arXiv_CV Image_Caption Review Caption Survey RNN Recognition
author: Zachary C. Lipton, John Berkowitz, Charles Elkan
---

* content
{:toc}

##### Abstract
Countless learning tasks require dealing with sequential data. Image captioning, speech synthesis, and music generation all require that a model produce outputs that are sequences. In other domains, such as time series prediction, video analysis, and musical information retrieval, a model must learn from inputs that are sequences. Interactive tasks, such as translating natural language, engaging in dialogue, and controlling a robot, often demand both capabilities. Recurrent neural networks (RNNs) are connectionist models that capture the dynamics of sequences via cycles in the network of nodes. Unlike standard feedforward neural networks, recurrent networks retain a state that can represent information from an arbitrarily long context window. Although recurrent neural networks have traditionally been difficult to train, and often contain millions of parameters, recent advances in network architectures, optimization techniques, and parallel computation have enabled successful large-scale learning with them. In recent years, systems based on long short-term memory (LSTM) and bidirectional (BRNN) architectures have demonstrated ground-breaking performance on tasks as varied as image captioning, language translation, and handwriting recognition. In this survey, we review and synthesize the research that over the past three decades first yielded and then made practical these powerful learning models. When appropriate, we reconcile conflicting notation and nomenclature. Our goal is to provide a self-contained explication of the state of the art together with a historical perspective and references to primary research.

##### Abstract (translated by Google)
无数的学习任务需要处理顺序数据。图像字幕，语音合成和音乐生成都需要一个模型产生序列的输出。在其他领域，如时间序列预测，视频分析和音乐信息检索，模型必须从输入序列中学习。诸如翻译自然语言，参与对话以及控制机器人等互动任务往往需要两种能力。递归神经网络（RNN）是连接模型，通过节点网络中的周期捕获序列的动态。与标准的前馈神经网络不同，循环网络保留一个状态，可以从任意长的上下文窗口中表示信息。尽管循环神经网络传统上难以训练，并且通常包含数百万个参数，但是网络架构，优化技术和并行计算方面的最新进展使得他们能够成功进行大规模的学习。近年来，基于长时间短时记忆（LSTM）和双向（BRNN）体系结构的系统在图像字幕，语言翻译和手写识别等任务上展现了突破性的性能。在这次调查中，我们回顾并综合了过去三十年来的研究成果，然后将这些强大的学习模式变为现实。在适当的时候，我们调和冲突的符号和术语。我们的目标是提供最先进的解释和历史观点，并参考主要研究。

##### URL
[https://arxiv.org/abs/1506.00019](https://arxiv.org/abs/1506.00019)

