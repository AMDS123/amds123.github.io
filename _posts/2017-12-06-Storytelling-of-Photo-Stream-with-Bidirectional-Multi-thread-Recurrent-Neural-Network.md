---
layout: post
title: 'Storytelling of Photo Stream with Bidirectional Multi-thread Recurrent Neural Network'
date: 2017-12-06 08:21:49
categories: arXiv_CV
tags: arXiv_CV Video_Caption Caption RNN
author: Yu Liu, Jianlong Fu, Tao Mei, Chang Wen Chen
---

* content
{:toc}

##### Abstract
Visual storytelling aims to generate human-level narrative language (i.e., a natural paragraph with multiple sentences) from a photo streams. A typical photo story consists of a global timeline with multi-thread local storylines, where each storyline occurs in one different scene. Such complex structure leads to large content gaps at scene transitions between consecutive photos. Most existing image/video captioning methods can only achieve limited performance, because the units in traditional recurrent neural networks (RNN) tend to "forget" the previous state when the visual sequence is inconsistent. In this paper, we propose a novel visual storytelling approach with Bidirectional Multi-thread Recurrent Neural Network (BMRNN). First, based on the mined local storylines, a skip gated recurrent unit (sGRU) with delay control is proposed to maintain longer range visual information. Second, by using sGRU as basic units, the BMRNN is trained to align the local storylines into the global sequential timeline. Third, a new training scheme with a storyline-constrained objective function is proposed by jointly considering both global and local matches. Experiments on three standard storytelling datasets show that the BMRNN model outperforms the state-of-the-art methods.

##### Abstract (translated by Google)
视觉叙事的目的是从照片流中产生人类叙事语言（即具有多个句子的自然段落）。一个典型的照片故事包括一个全球时间线与多线程本地故事情节，其中每个故事情节发生在一个不同的场景。这种复杂的结构导致在连续照片之间的场景转换处有大的内容空白。大多数现有的图像/视频字幕方法只能达到有限的性能，因为当视觉序列不一致时，传统递归神经网络（RNN）中的单元倾向于“忘记”以前的状态。在本文中，我们提出了一种新颖的双向多线程递归神经网络（BMRNN）的视觉叙事方法。首先，根据本地的故事情节，提出了一个带有延迟控制的跳过门控循环单元（sGRU），以保持更远距离的视觉信息。其次，通过使用sGRU作为基本单位，BMRNN接受培训，将本地故事情节整合到全球连续时间表中。第三，通过联合考虑全球和地方的匹配，提出了一种新的具有故事情节约束目标函数的训练方案。三个标准叙事数据集上的实验表明，BMRNN模型胜过了最先进的方法。

##### URL
[https://arxiv.org/abs/1606.00625](https://arxiv.org/abs/1606.00625)

