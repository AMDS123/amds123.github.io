---
layout: post
title: 'Video Captioning with Guidance of Multimodal Latent Topics'
date: 2017-12-06 02:32:56
categories: arXiv_CV
tags: arXiv_CV Video_Caption Caption
author: Shizhe Chen, Jia Chen, Qin Jin, Alexander Hauptmann
---

* content
{:toc}

##### Abstract
The topic diversity of open-domain videos leads to various vocabularies and linguistic expressions in describing video contents, and therefore, makes the video captioning task even more challenging. In this paper, we propose an unified caption framework, M&M TGM, which mines multimodal topics in unsupervised fashion from data and guides the caption decoder with these topics. Compared to pre-defined topics, the mined multimodal topics are more semantically and visually coherent and can reflect the topic distribution of videos better. We formulate the topic-aware caption generation as a multi-task learning problem, in which we add a parallel task, topic prediction, in addition to the caption task. For the topic prediction task, we use the mined topics as the teacher to train a student topic prediction model, which learns to predict the latent topics from multimodal contents of videos. The topic prediction provides intermediate supervision to the learning process. As for the caption task, we propose a novel topic-aware decoder to generate more accurate and detailed video descriptions with the guidance from latent topics. The entire learning procedure is end-to-end and it optimizes both tasks simultaneously. The results from extensive experiments conducted on the MSR-VTT and Youtube2Text datasets demonstrate the effectiveness of our proposed model. M&M TGM not only outperforms prior state-of-the-art methods on multiple evaluation metrics and on both benchmark datasets, but also achieves better generalization ability.

##### Abstract (translated by Google)
开放域视频的话题多样性导致了描述视频内容的各种词汇和语言表达，因此使视频字幕的任务更具挑战性。在本文中，我们提出了一个统一的字幕框架，M＆M TGM，它以无监督的方式从数据中挖掘多模态话题，并引导字幕译码器处理这些话题。与预先定义的主题相比，挖掘的多模态话题在语义和视觉上更加一致，能更好地反映视频的话题分布。我们将话题感知字幕生成制定为多任务学习问题，除了字幕任务之外，还增加了并行任务，话题预测。对于话题预测任务，我们使用挖掘出来的话题作为老师来训练一个学生话题预测模型，学习从视频多模式内容中预测潜在话题。话题预测提供了对学习过程的中间监督。对于字幕任务，我们提出了一种新颖的主题感知解码器，以潜在主题为指导，生成更精确，更详细的视频描述。整个学习过程是端到端的，它同时优化了这两个任务。在MSR-VTT和Youtube2Text数据集上进行的大量实验的结果证明了我们提出的模型的有效性。 M＆M TGM不仅比多种评估指标和基准数据集上先进的方法优越，而且具有更好的泛化能力。

##### URL
[https://arxiv.org/abs/1708.09667](https://arxiv.org/abs/1708.09667)

