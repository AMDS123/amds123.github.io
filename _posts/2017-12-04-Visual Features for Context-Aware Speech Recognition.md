---
layout: post
title:  'Visual Features for Context-Aware Speech Recognition'
date:   2017-12-05 18:47:33
categories: CV
tags: CV
author: Abhinav Gupta, Yajie Miao, Leonardo Neves, Florian Metze
---

* content
{:toc}

##### Abstract
Automatic transcriptions of consumer-generated multi-media content such as "Youtube" videos still exhibit high word error rates. Such data typically occupies a very broad domain, has been recorded in challenging conditions, with cheap hardware and a focus on the visual modality, and may have been post-processed or edited. In this paper, we extend our earlier work on adapting the acoustic model of a DNN-based speech recognition system to an RNN language model and show how both can be adapted to the objects and scenes that can be automatically detected in the video. We are working on a corpus of "how-to" videos from the web, and the idea is that an object that can be seen ("car"), or a scene that is being detected ("kitchen") can be used to condition both models on the "context" of the recording, thereby reducing perplexity and improving transcription. We achieve good improvements in both cases and compare and analyze the respective reductions in word error rate. We expect that our results can be used for any type of speech processing in which "context" information is available, for example in robotics, man-machine interaction, or when indexing large audio-visual archives, and should ultimately help to bring together the "video-to-text" and "speech-to-text" communities.

##### Abstract (translated by Google)
消费者生成的多媒体内容（例如“Youtube”视频）的自动转录依然表现出高的字错误率。这些数据通常占据非常广泛的领域，已经被记录在具有挑战性的条件下，以便宜的硬件和对视觉形式的关注，并且可能已经被后处理或编辑。在本文中，我们扩展了我们早先的工作，将基于DNN的语音识别系统的声学模型适配到RNN语言模型，并展示如何将两者适配到可以在视频中自动检测的对象和场景。我们正在从网络上制作一系列“how-to”视频，其思想是可以看到的对象（“汽车”）或正在被检测到的场景（“厨房”）可用于在记录的“背景”中调节两个模型，从而减少困惑并改善转录。我们在这两种情况下都取得了很好的改进，并比较和分析了单词错误率的降低。我们期望我们的结果可以用于任何类型的可以获得“上下文”信息的语音处理，例如在机器人，人机交互或索引大型音像档案时，最终可以帮助把“视频到文本”和“语音到文本”社区。

##### URL
[http://arxiv.org/abs/1712.00489](http://arxiv.org/abs/1712.00489)

