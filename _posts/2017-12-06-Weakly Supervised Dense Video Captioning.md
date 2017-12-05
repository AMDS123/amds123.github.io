---
layout: post
title: 'Weakly Supervised Dense Video Captioning'
date: 2017-12-06 02:46:07
categories: arXiv_CV
tags: arXiv_CV Video_Caption Weakly_Supervised Caption CNN
author: Zhiqiang Shen, Jianguo Li, Zhou Su, Minjun Li, Yurong Chen, Yu-Gang Jiang, Xiangyang Xue
---

* content
{:toc}

##### Abstract
This paper focuses on a novel and challenging vision task, dense video captioning, which aims to automatically describe a video clip with multiple informative and diverse caption sentences. The proposed method is trained without explicit annotation of fine-grained sentence to video region-sequence correspondence, but is only based on weak video-level sentence annotations. It differs from existing video captioning systems in three technical aspects. First, we propose lexical fully convolutional neural networks (Lexical-FCN) with weakly supervised multi-instance multi-label learning to weakly link video regions with lexical labels. Second, we introduce a novel submodular maximization scheme to generate multiple informative and diverse region-sequences based on the Lexical-FCN outputs. A winner-takes-all scheme is adopted to weakly associate sentences to region-sequences in the training phase. Third, a sequence-to-sequence learning based language model is trained with the weakly supervised information obtained through the association process. We show that the proposed method can not only produce informative and diverse dense captions, but also outperform state-of-the-art single video captioning methods by a large margin.

##### Abstract (translated by Google)
本文着重于一个新颖而具有挑战性的视觉任务，即密集的视频字幕，其目的是自动描述具有多种多样的信息和多样的字幕语句的视频剪辑。本文提出的方法是在没有明确的视频序列对应的细粒度句子的情况下进行训练，而只是基于弱视频水平的句子注释。它与三个技术方面的现有视频字幕系统不同。首先，我们提出了带有弱监督多实例多标签学习的词汇完全卷积神经网络（Lexical-FCN），将视频区域与词汇标签弱链接。其次，我们引入一种新的子模块最大化方案，基于词汇FCN输出产生多个信息多样的区域序列。在训练阶段采用“胜者全得”方案，将句子与地区序列弱联系起来。第三，通过关联过程获得的弱监督信息训练基于序列学习的语言模型。我们表明，提出的方法不仅可以产生丰富多彩的密集字幕，而且还大大超越了最先进的单一视频字幕的方法。

##### URL
[https://arxiv.org/abs/1704.01502](https://arxiv.org/abs/1704.01502)

