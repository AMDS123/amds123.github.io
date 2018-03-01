---
layout: post
title: "Pop Music Highlighter: Marking the Emotion Keypoints"
date: 2018-02-28 16:02:47
categories: arXiv_AI
tags: arXiv_AI Attention CNN Classification
author: Yu-Siang Huang, Szu-Yu Chou, Yi-Hsuan Yang
mathjax: true
---

* content
{:toc}

##### Abstract
The goal of music highlight extraction is to get a short consecutive segment of a piece of music that provides an effective representation of the whole piece. In a previous work, we introduced an attention-based convolutional recurrent neural network that uses music emotion classification as a surrogate task for music highlight extraction, for Pop songs. The rationale behind that approach is that the highlight of a song is usually the most emotional part. This paper extends our previous work in the following two aspects. First, methodology-wise we experiment with a new architecture that does not need any recurrent layers, making the training process faster. Moreover, we compare a late-fusion variant and an early-fusion variant to study which one better exploits the attention mechanism. Second, we conduct and report an extensive set of experiments comparing the proposed attention-based methods against a heuristic energy-based method, a structural repetition-based method, and a few other simple feature-based methods for this task. Due to the lack of public-domain labeled data for highlight extraction, following our previous work we use the RWC POP 100-song data set to evaluate how the detected highlights overlap with any chorus sections of the songs. The experiments demonstrate the effectiveness of our methods over competing methods. For reproducibility, we open source the code and pre-trained model at https://github.com/remyhuang/pop-music-highlighter/.

##### Abstract (translated by Google)
音乐高光提取的目标是获得一段音乐的连续片段，为整片提供有效的表示。在以前的工作中，我们引入了基于注意力的卷积递归神经网络，该算法使用音乐情感分类作为音乐高光提取的替代任务，用于流行歌曲。这种方法背后的基本原理是，一首歌的亮点通常是最情绪化的部分。本文从以下两个方面扩展了我们以前的工作。首先，在方法论方面，我们尝试使用不需要任何经常性图层的新架构，从而加快培训过程。此外，我们比较了一个晚期融合变体和一个早期融合变体，以研究哪一个更好地利用了关注机制。其次，我们进行并报告了一系列广泛的实验，将提出的基于注意力的方法与启发式基于能量的方法，基于结构重复的方法以及其他一些简单的基于特征的方法进行比较。由于缺乏用于高光提取的公共领域标记数据，继我们之前的工作，我们使用RWC POP 100-歌曲数据集来评估检测到的高光与歌曲的任何合唱部分重叠的方式。实验证明我们的方法胜过竞争方法的有效性。为了再现性，我们在https://github.com/remyhuang/pop-music-highlighter/上开源代码和预先训练的模型。

##### URL
[http://arxiv.org/abs/1802.10495](http://arxiv.org/abs/1802.10495)

##### PDF
[http://arxiv.org/pdf/1802.10495](http://arxiv.org/pdf/1802.10495)

