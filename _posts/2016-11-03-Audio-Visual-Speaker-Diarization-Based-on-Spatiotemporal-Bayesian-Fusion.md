---
layout: post
title: "Audio-Visual Speaker Diarization Based on Spatiotemporal Bayesian Fusion"
date: 2016-11-03 16:40:24
categories: arXiv_CV
tags: arXiv_CV Tracking Inference
author: Israel D. Gebru, Silèye Ba, Xiaofei Li, Radu Horaud
mathjax: true
---

* content
{:toc}

##### Abstract
Speaker diarization consists of assigning speech signals to people engaged in a dialogue. An audio-visual spatiotemporal diarization model is proposed. The model is well suited for challenging scenarios that consist of several participants engaged in multi-party interaction while they move around and turn their heads towards the other participants rather than facing the cameras and the microphones. Multiple-person visual tracking is combined with multiple speech-source localization in order to tackle the speech-to-person association problem. The latter is solved within a novel audio-visual fusion method on the following grounds: binaural spectral features are first extracted from a microphone pair, then a supervised audio-visual alignment technique maps these features onto an image, and finally a semi-supervised clustering method assigns binaural spectral features to visible persons. The main advantage of this method over previous work is that it processes in a principled way speech signals uttered simultaneously by multiple persons. The diarization itself is cast into a latent-variable temporal graphical model that infers speaker identities and speech turns, based on the output of an audio-visual association process, executed at each time slice, and on the dynamics of the diarization variable itself. The proposed formulation yields an efficient exact inference procedure. A novel dataset, that contains audio-visual training data as well as a number of scenarios involving several participants engaged in formal and informal dialogue, is introduced. The proposed method is thoroughly tested and benchmarked with respect to several state-of-the art diarization algorithms.

##### Abstract (translated by Google)
演讲者diarization包括分配语音信号给​​参与对话的人。提出了一个视听时空二元化模型。该模型非常适合挑战场景，这些场景包括多个参与者进行多方互动，而他们四处走动，将头转向其他参与者，而不是面对相机和麦克风。多人视觉跟踪与多个语音源本地化相结合，以解决语音与人之间的关联问题。后者在一种新颖的视听融合方法中被解决，理由如下：首先从麦克风对提取双耳光谱特征，然后有监督的视听对准技术将这些特征映射到图像上，最后是半监督聚类方法将双耳光谱特征分配给可见人。这种方法相对于以前的工作的主要优点是它能够以一种原则的方式处理由多人同时发出的语音信号。二元化本身被投入到一个潜变量时间图模型中，该模型基于在每个时间片上执行的音频 - 视觉关联过程的输出以及二元变量本身的动态性来推断说话者身份和语音转向。所提出的配方产生了有效的精确推理过程。介绍了一个新的数据集，其中包含视听训练数据以及涉及参与正式和非正式对话的若干参与者的一些场景。所提出的方法是经过彻底的测试和基准的几个先进的diarization算法。

##### URL
[https://arxiv.org/abs/1603.09725](https://arxiv.org/abs/1603.09725)

##### PDF
[https://arxiv.org/pdf/1603.09725](https://arxiv.org/pdf/1603.09725)

