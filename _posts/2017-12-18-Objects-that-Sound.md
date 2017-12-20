---
layout: post
title: "Objects that Sound"
date: 2017-12-18 19:52:53
categories: arXiv_CV
tags: arXiv_CV Embedding
author: Relja Arandjelovi&#x107;, Andrew Zisserman
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper our objectives are, first, networks that can embed audio and visual inputs into a common space that is suitable for cross-modal retrieval; and second, a network that can localize the object that sounds in an image, given the audio signal. We achieve both these objectives by training from unlabelled video using only audio-visual correspondence (AVC) as the objective function. This is a form of cross-modal self-supervision from video. 
 To this end, we design new network architectures that can be trained using the AVC task for these functionalities: for cross-modal retrieval, and for localizing the source of a sound in an image. We make the following contributions: (i) show that audio and visual embedding can be learnt that enable both within-mode (e.g. audio-to-audio) and between-mode retrieval; (ii) explore various architectures for the AVC task, including those for the visual stream that ingest a single image, or multiple images, or a single image and multi-frame optical flow; (iii) show that the semantic object that sounds within an image can be localized (using only the sound, no motion or flow information); and (iv) give a cautionary tale in how to avoid undesirable shortcuts in the data preparation.

##### Abstract (translated by Google)
在本文中，我们的目标首先是将音频和视觉输入嵌入到适用于跨模式检索的公共空间的网络;其次，给定音频信号的网络可以定位在图像中发出的对象。我们通过仅使用视听对应（AVC）作为目标函数的未标记视频的训练来实现这两个目标。这是视频的一种跨模式自我监督。
 为此，我们设计了新的网络体系结构，可以使用AVC任务对这些功能进行训练：跨模式检索，以及在图像中定位声音的来源。我们做出如下贡献：（i）显示音频和视频嵌入可以被学习，使得能够在模式内（例如，音频 - 音频）和模式间检索; （ii）探索用于AVC任务的各种体系结构，包括用于摄取单个图像或多个图像的视觉流，或单个图像和多帧光流的结构; （iii）表明图像中的语义对象可以被本地化（仅使用声音，没有运动或流量信息）; （iv）就如何避免数据准备中不需要的快捷方式提出警示。

##### URL
[http://arxiv.org/abs/1712.06651](http://arxiv.org/abs/1712.06651)

##### PDF
[http://arxiv.org/pdf/1712.06651](http://arxiv.org/pdf/1712.06651)

