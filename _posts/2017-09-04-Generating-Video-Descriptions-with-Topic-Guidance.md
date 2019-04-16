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


##### URL
[https://arxiv.org/abs/1708.09666](https://arxiv.org/abs/1708.09666)

##### PDF
[https://arxiv.org/pdf/1708.09666](https://arxiv.org/pdf/1708.09666)

