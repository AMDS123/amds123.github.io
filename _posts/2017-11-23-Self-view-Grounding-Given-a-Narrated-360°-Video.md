---
layout: post
title: "Self-view Grounding Given a Narrated 360° Video"
date: 2017-11-23 12:06:20
categories: arXiv_CV
tags: arXiv_CV Attention CNN RNN
author: Shih-Han Chou, Yi-Chun Chen, Kuo-Hao Zeng, Hou-Ning Hu, Jianlong Fu, Min Sun
mathjax: true
---

* content
{:toc}

##### Abstract
Narrated 360{\deg} videos are typically provided in many touring scenarios to mimic real-world experience. However, previous work has shown that smart assistance (i.e., providing visual guidance) can significantly help users to follow the Normal Field of View (NFoV) corresponding to the narrative. In this project, we aim at automatically grounding the NFoVs of a 360{\deg} video given subtitles of the narrative (referred to as "NFoV-grounding"). We propose a novel Visual Grounding Model (VGM) to implicitly and efficiently predict the NFoVs given the video content and subtitles. Specifically, at each frame, we efficiently encode the panorama into feature map of candidate NFoVs using a Convolutional Neural Network (CNN) and the subtitles to the same hidden space using an RNN with Gated Recurrent Units (GRU). Then, we apply soft-attention on candidate NFoVs to trigger sentence decoder aiming to minimize the reconstruct loss between the generated and given sentence. Finally, we obtain the NFoV as the candidate NFoV with the maximum attention without any human supervision. To train VGM more robustly, we also generate a reverse sentence conditioning on one minus the soft-attention such that the attention focuses on candidate NFoVs less relevant to the given sentence. The negative log reconstruction loss of the reverse sentence (referred to as "irrelevant loss") is jointly minimized to encourage the reverse sentence to be different from the given sentence. To evaluate our method, we collect the first narrated 360{\deg} videos dataset and achieve state-of-the-art NFoV-grounding performance.

##### Abstract (translated by Google)
为了模拟真实世界的体验，通常在许多旅游场景中提供了360°{\ deg}视频。然而，以前的工作表明，智能辅助（即提供视觉指导）可以显着帮助用户遵循与叙述相对应的正常视野（NFoV）。在这个项目中，我们的目标是自动接通360度视频的NFoV，给出叙述的字幕（称为“NFoV-接地”）。我们提出了一种新颖的视觉接地模型（VGM），以隐式和有效地预测给定视频内容和字幕的NFoV。具体而言，在每一帧，我们有效地编码全景成候选NFoVs使用卷积神经网络（CNN）的特征地图和字幕到相同的隐藏空间使用RNN与门控重复单元（GRU）。然后，我们对候选NFoVs进行软注释，以触发句子解码器，以最小化生成和给定句子之间的重构损失。最后，我们在没有任何人力监督的情况下，最大限度地获得NFoV作为候选NFoV。为了更加强健地训练VGM，我们还在一个减去软注意力的情况下产生反向语句调节，使得注意力集中在与给定句子不太相关的候选NFoV上。将反向句的负对数重构损失（称为“不相关损失”）联合最小化以鼓励反向句与给定句子不同。为了评估我们的方法，我们收集了第一个叙述的360度视频数据集，并实现了最先进的NFoV接地性能。

##### URL
[https://arxiv.org/abs/1711.08664](https://arxiv.org/abs/1711.08664)

##### PDF
[https://arxiv.org/pdf/1711.08664](https://arxiv.org/pdf/1711.08664)

