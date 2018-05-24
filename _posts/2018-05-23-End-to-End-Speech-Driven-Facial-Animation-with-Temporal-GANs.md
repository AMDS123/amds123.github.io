---
layout: post
title: "End-to-End Speech-Driven Facial Animation with Temporal GANs"
date: 2018-05-23 17:54:32
categories: arXiv_SD
tags: arXiv_SD Knowledge GAN
author: Konstantinos Vougioukas, Stavros Petridis, Maja Pantic
mathjax: true
---

* content
{:toc}

##### Abstract
Speech-driven facial animation is the process which uses speech signals to automatically synthesize a talking character. The majority of work in this domain creates a mapping from audio features to visual features. This often requires post-processing using computer graphics techniques to produce realistic albeit subject dependent results. We present a system for generating videos of a talking head, using a still image of a person and an audio clip containing speech, that doesn't rely on any handcrafted intermediate features. To the best of our knowledge, this is the first method capable of generating subject independent realistic videos directly from raw audio. Our method can generate videos which have (a) lip movements that are in sync with the audio and (b) natural facial expressions such as blinks and eyebrow movements. We achieve this by using a temporal GAN with 2 discriminators, which are capable of capturing different aspects of the video. The effect of each component in our system is quantified through an ablation study. The generated videos are evaluated based on their sharpness, reconstruction quality, and lip-reading accuracy. Finally, a user study is conducted, confirming that temporal GANs lead to more natural sequences than a static GAN-based approach.

##### Abstract (translated by Google)
语音驱动的面部动画是使用语音信号自动合成说话人物的过程。该领域的大部分工作创建了从音频功能到视觉功能的映射。这通常需要使用计算机图形技术进行后处理以产生真实的依赖于受试者的结果。我们提出了一种用于生成说话头的视频的系统，该系统使用人的静止图像和包含语音的音频片段，其不依赖任何手工制作的中间特征。就我们所知，这是第一种能够直接从原始音频生成主题独立真实视频的方法。我们的方法可以生成具有以下特征的视频：（a）与音频同步的嘴唇运动和（b）眨眼和眉毛运动等自然面部表情。我们通过使用具有2个鉴别器的时间GAN来实现这一点，这些鉴别器能够捕捉视频的不同方面。通过消融研究来量化我们系统中每个组分的影响。生成的视频根据其清晰度，重建质量和唇读精度进行评估。最后，进行用户研究，证实时间GAN比静态GAN方法导致更多的自然序列。

##### URL
[http://arxiv.org/abs/1805.09313](http://arxiv.org/abs/1805.09313)

##### PDF
[http://arxiv.org/pdf/1805.09313](http://arxiv.org/pdf/1805.09313)

