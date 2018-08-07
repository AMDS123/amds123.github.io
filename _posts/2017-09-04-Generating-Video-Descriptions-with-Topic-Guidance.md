---
layout: post
title: "Generating Video Descriptions with Topic Guidance"
date: 2017-09-04 11:38:38
categories: arXiv_CV
tags: arXiv_CV Image_Caption Video_Caption Caption Prediction
author: Shizhe Chen, Jia Chen, Qin Jin
mathjax: true
---

* content
{:toc}

##### Abstract
Generating video descriptions in natural language (a.k.a. video captioning) is a more challenging task than image captioning as the videos are intrinsically more complicated than images in two aspects. First, videos cover a broader range of topics, such as news, music, sports and so on. Second, multiple topics could coexist in the same video. In this paper, we propose a novel caption model, topic-guided model (TGM), to generate topic-oriented descriptions for videos in the wild via exploiting topic information. In addition to predefined topics, i.e., category tags crawled from the web, we also mine topics in a data-driven way based on training captions by an unsupervised topic mining model. We show that data-driven topics reflect a better topic schema than the predefined topics. As for testing video topic prediction, we treat the topic mining model as teacher to train the student, the topic prediction model, by utilizing the full multi-modalities in the video especially the speech modality. We propose a series of caption models to exploit topic guidance, including implicitly using the topics as input features to generate words related to the topic and explicitly modifying the weights in the decoder with topics to function as an ensemble of topic-aware language decoders. Our comprehensive experimental results on the current largest video caption dataset MSR-VTT prove the effectiveness of our topic-guided model, which significantly surpasses the winning performance in the 2016 MSR video to language challenge.

##### Abstract (translated by Google)
以自然语言（例如视频字幕）生成视频描述比图像字幕更具挑战性，因为视频在本质上比图像在两个方面更复杂。首先，视频涵盖更广泛的主题，如新闻，音乐，体育等。其次，多个主题可以在同一视频中共存。在本文中，我们提出了一种新颖的标题模型，即主题引导模型（TGM），通过利用主题信息为野外视频生成面向主题的描述。除了预定义的主题，即从Web抓取的类别标签之外，我们还基于无监督的主题挖掘模型的训练标题以数据驱动的方式挖掘主题。我们表明，数据驱动的主题反映了比预定义主题更好的主题模式。对于测试视频主题预测，我们将主题挖掘模型作为教师来训练学生，主题预测模型，利用视频中的完整多模态，特别是语音模态。我们提出了一系列标题模型来利用主题指导，包括隐式地使用主题作为输入特征来生成与主题相关的单词，并明确地修改解码器中的权重，主题用作主题感知语言解码器的集合。我们对当前最大的视频字幕数据集MSR-VTT的全面实验结果证明了我们的主题指导模型的有效性，该模型显着超越了2016年MSR视频到语言挑战的获胜表现。

##### URL
[https://arxiv.org/abs/1708.09666](https://arxiv.org/abs/1708.09666)

##### PDF
[https://arxiv.org/pdf/1708.09666](https://arxiv.org/pdf/1708.09666)

