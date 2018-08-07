---
layout: post
title: "Video Captioning with Guidance of Multimodal Latent Topics"
date: 2017-09-02 15:34:44
categories: arXiv_CV
tags: arXiv_CV Video_Caption Caption Prediction
author: Shizhe Chen, Jia Chen, Qin Jin, Alexander Hauptmann
mathjax: true
---

* content
{:toc}

##### Abstract
The topic diversity of open-domain videos leads to various vocabularies and linguistic expressions in describing video contents, and therefore, makes the video captioning task even more challenging. In this paper, we propose an unified caption framework, M&M TGM, which mines multimodal topics in unsupervised fashion from data and guides the caption decoder with these topics. Compared to pre-defined topics, the mined multimodal topics are more semantically and visually coherent and can reflect the topic distribution of videos better. We formulate the topic-aware caption generation as a multi-task learning problem, in which we add a parallel task, topic prediction, in addition to the caption task. For the topic prediction task, we use the mined topics as the teacher to train a student topic prediction model, which learns to predict the latent topics from multimodal contents of videos. The topic prediction provides intermediate supervision to the learning process. As for the caption task, we propose a novel topic-aware decoder to generate more accurate and detailed video descriptions with the guidance from latent topics. The entire learning procedure is end-to-end and it optimizes both tasks simultaneously. The results from extensive experiments conducted on the MSR-VTT and Youtube2Text datasets demonstrate the effectiveness of our proposed model. M&M TGM not only outperforms prior state-of-the-art methods on multiple evaluation metrics and on both benchmark datasets, but also achieves better generalization ability.

##### Abstract (translated by Google)
开放域视频的主题多样性导致在描述视频内容时出现各种词汇和语言表达，因此使得视频字幕任务更具挑战性。在本文中，我们提出了一个统一的标题框架，即M＆M TGM，它以无人监督的方式从数据中挖掘多模态主题，并引导字幕解码器使用这些主题。与预定义的主题相比，挖掘的多模式主题在语义和视觉上更加连贯，并且可以更好地反映视频的主题分布。我们将主题感知字幕生成表示为多任务学习问题，除了标题任务之外，我们还在其中添加并行任务，主题预测。对于主题预测任务，我们使用挖掘的主题作为教师来训练学生主题预测模型，该模型学习从视频的多模态内容预测潜在主题。主题预测为学习过程提供中间监督。至于字幕任务，我们提出了一种新颖的主题感知解码器，可以在潜在主题的指导下生成更准确和详细的视频描述。整个学习过程是端到端的，它同时优化了两个任务。在MSR-VTT和Youtube2Text数据集上进行的大量实验的结果证明了我们提出的模型的有效性。 M＆M TGM不仅在多个评估指标和基准数据集上都优于先前的最先进方法，而且还实现了更好的泛化能力。

##### URL
[https://arxiv.org/abs/1708.09667](https://arxiv.org/abs/1708.09667)

##### PDF
[https://arxiv.org/pdf/1708.09667](https://arxiv.org/pdf/1708.09667)

