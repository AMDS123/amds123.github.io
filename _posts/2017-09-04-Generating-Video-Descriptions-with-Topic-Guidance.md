---
layout: post
title: "Generating Video Descriptions with Topic Guidance"
date: 2017-09-04 11:38:38
categories: arXiv_CV
tags: arXiv_CV Image_Caption Video_Caption Caption
author: Shizhe Chen, Jia Chen, Qin Jin
mathjax: true
---

* content
{:toc}

##### Abstract
Generating video descriptions in natural language (a.k.a. video captioning) is a more challenging task than image captioning as the videos are intrinsically more complicated than images in two aspects. First, videos cover a broader range of topics, such as news, music, sports and so on. Second, multiple topics could coexist in the same video. In this paper, we propose a novel caption model, topic-guided model (TGM), to generate topic-oriented descriptions for videos in the wild via exploiting topic information. In addition to predefined topics, i.e., category tags crawled from the web, we also mine topics in a data-driven way based on training captions by an unsupervised topic mining model. We show that data-driven topics reflect a better topic schema than the predefined topics. As for testing video topic prediction, we treat the topic mining model as teacher to train the student, the topic prediction model, by utilizing the full multi-modalities in the video especially the speech modality. We propose a series of caption models to exploit topic guidance, including implicitly using the topics as input features to generate words related to the topic and explicitly modifying the weights in the decoder with topics to function as an ensemble of topic-aware language decoders. Our comprehensive experimental results on the current largest video caption dataset MSR-VTT prove the effectiveness of our topic-guided model, which significantly surpasses the winning performance in the 2016 MSR video to language challenge.

##### Abstract (translated by Google)
以自然语言（也称为视频字幕）生成视频描述是比图像字幕更具挑战性的任务，因为在两个方面视频本质上比图像复杂。首先，视频涵盖了更广泛的话题，如新闻，音乐，体育等。其次，多个主题可以在同一个视频中共存。在本文中，我们提出了一种新颖的标题模型，主题引导模型（TGM），通过利用主题信息为野外视频生成面向主题的描述。除了预定义的主题，即从网络爬取的类别标签之外，我们还通过无监督的主题挖掘模型基于训练标题以数据驱动的方式挖掘主题。我们显示数据驱动的主题反映了比预定义主题更好的主题模式。在测试视频话题预测方面，我们将话题挖掘模型作为教师，利用视频中的全多方式，特别是语音方式，对学生，话题预测模型进行训练。我们提出了一系列的标题模型来利用主题引导，包括隐含地使用主题作为输入特征来生成与主题相关的词，并且明确地修改具有主题的解码器中的权重以用作主题感知型语言解码器的集合。我们在当前最大的视频字幕数据集MSR-VTT上的综合实验结果证明了我们的话题指导模型的有效性，这显着超越了2016年MSR视频到语言挑战的胜利表现。

##### URL
[https://arxiv.org/abs/1708.09666](https://arxiv.org/abs/1708.09666)

##### PDF
[https://arxiv.org/pdf/1708.09666](https://arxiv.org/pdf/1708.09666)

