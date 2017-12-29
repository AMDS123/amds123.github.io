---
layout: post
title: "A Light-Weight Multimodal Framework for Improved Environmental Audio Tagging"
date: 2017-12-27 20:52:21
categories: arXiv_SD
tags: arXiv_SD Sentiment Embedding CNN RNN Recognition
author: Juncheng Li, Yun Wang, Joseph Szurley, Florian Metze, Samarjit Das
mathjax: true
---

* content
{:toc}

##### Abstract
The lack of strong labels has severely limited the state-of-the-art fully supervised audio tagging systems to be scaled to larger dataset. Meanwhile, audio-visual learning models based on unlabeled videos have been successfully applied to audio tagging, but they are inevitably resource hungry and require a long time to train. In this work, we propose a light-weight, multimodal framework for environmental audio tagging. The audio branch of the framework is a convolutional and recurrent neural network (CRNN) based on multiple instance learning (MIL). It is trained with the audio tracks of a large collection of weakly labeled YouTube video excerpts; the video branch uses pretrained state-of-the-art image recognition networks and word embeddings to extract information from the video track and to map visual objects to sound events. Experiments on the audio tagging task of the DCASE 2017 challenge show that the incorporation of video information improves a strong baseline audio tagging system by 5.3\% absolute in terms of $F_1$ score. The entire system can be trained within 6~hours on a single GPU, and can be easily carried over to other audio tasks such as speech sentimental analysis.

##### Abstract (translated by Google)
缺乏强大的标签严重限制了最先进的完全监督的音频标签系统被缩放到更大的数据集。同时，基于未标注视频的视听学习模型已经成功地应用于音频标签，但是它们不可避免地需要资源，需要很长时间的训练。在这项工作中，我们提出了一个轻量级的环境音频标签多模式框架。该框架的音频分支是基于多实例学习（MIL）的卷积和递归神经网络（CRNN）。它被训练与音频轨道的大量弱标记的YouTube视频摘录;视频分支使用预训练的最先进的图像识别网络和文字嵌入来从视频轨道提取信息并将视觉对象映射到声音事件。对DCASE 2017挑战音频标签任务的实验表明，视频信息的合并改善了强大的基线音频标签系统，在$ F_1 $分数方面提高了5.3％。整个系统可以在6个小时内在单个GPU上训练，并且可以轻松地转移到其他音频任务，如语音感伤分析。

##### URL
[https://arxiv.org/abs/1712.09680](https://arxiv.org/abs/1712.09680)

##### PDF
[https://arxiv.org/pdf/1712.09680](https://arxiv.org/pdf/1712.09680)

