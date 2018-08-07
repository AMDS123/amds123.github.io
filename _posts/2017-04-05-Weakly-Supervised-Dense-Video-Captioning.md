---
layout: post
title: "Weakly Supervised Dense Video Captioning"
date: 2017-04-05 16:06:09
categories: arXiv_CV
tags: arXiv_CV Video_Caption Weakly_Supervised Caption CNN Language_Model
author: Zhiqiang Shen, Jianguo Li, Zhou Su, Minjun Li, Yurong Chen, Yu-Gang Jiang, Xiangyang Xue
mathjax: true
---

* content
{:toc}

##### Abstract
This paper focuses on a novel and challenging vision task, dense video captioning, which aims to automatically describe a video clip with multiple informative and diverse caption sentences. The proposed method is trained without explicit annotation of fine-grained sentence to video region-sequence correspondence, but is only based on weak video-level sentence annotations. It differs from existing video captioning systems in three technical aspects. First, we propose lexical fully convolutional neural networks (Lexical-FCN) with weakly supervised multi-instance multi-label learning to weakly link video regions with lexical labels. Second, we introduce a novel submodular maximization scheme to generate multiple informative and diverse region-sequences based on the Lexical-FCN outputs. A winner-takes-all scheme is adopted to weakly associate sentences to region-sequences in the training phase. Third, a sequence-to-sequence learning based language model is trained with the weakly supervised information obtained through the association process. We show that the proposed method can not only produce informative and diverse dense captions, but also outperform state-of-the-art single video captioning methods by a large margin.

##### Abstract (translated by Google)
本文重点介绍一种新颖且具有挑战性的视觉任务，即密集视频字幕，旨在自动描述具有多个信息性和多样化字幕句子的视频剪辑。所提出的方法是在没有对细粒度句子的明确注释到视频区域 - 序列对应的情况下训练的，而是仅基于弱视频级句子注释。它在三个技术方面不同于现有的视频字幕系统。首先，我们提出词汇完全卷积神经网络（Lexical-FCN）与弱监督多实例多标签学习，以弱化链接视频区域与词汇标签。其次，我们引入了一种新颖的子模块最大化方案，以基于Lexical-FCN输出生成多个信息丰富且多样化的区域序列。采用赢者通吃方案在训练阶段将句子与区域序列弱关联。第三，基于序列到序列学习的语言模型用通过关联过程获得的弱监督信息进行训练。我们证明了所提出的方法不仅可以产生信息丰富且多样化的密集字幕，而且还可以大幅度地优于最先进的单视频字幕方法。

##### URL
[https://arxiv.org/abs/1704.01502](https://arxiv.org/abs/1704.01502)

##### PDF
[https://arxiv.org/pdf/1704.01502](https://arxiv.org/pdf/1704.01502)

