---
layout: post
title: "Conditioning Deep Generative Raw Audio Models for Structured Automatic Music"
date: 2018-06-26 11:10:19
categories: arXiv_SD
tags: arXiv_SD Deep_Learning
author: Rachel Manzelli, Vijay Thakkar, Ali Siahkamari, Brian Kulis
mathjax: true
---

* content
{:toc}

##### Abstract
Existing automatic music generation approaches that feature deep learning can be broadly classified into two types: raw audio models and symbolic models. Symbolic models, which train and generate at the note level, are currently the more prevalent approach; these models can capture long-range dependencies of melodic structure, but fail to grasp the nuances and richness of raw audio generations. Raw audio models, such as DeepMind's WaveNet, train directly on sampled audio waveforms, allowing them to produce realistic-sounding, albeit unstructured music. In this paper, we propose an automatic music generation methodology combining both of these approaches to create structured, realistic-sounding compositions. We consider a Long Short Term Memory network to learn the melodic structure of different styles of music, and then use the unique symbolic generations from this model as a conditioning input to a WaveNet-based raw audio generator, creating a model for automatic, novel music. We then evaluate this approach by showcasing results of this work.

##### Abstract (translated by Google)
具有深度学习功能的现有自动音乐生成方法大致可分为两种类型：原始音频模型和符号模型。在音符级别训练和生成的符号模型是目前比较流行的方法;这些模型可以捕捉旋律结构的长程依赖性，但无法掌握原始音频世代的细微差别和丰富性。 RawMind的WaveNet等原始音频模型直接训练采样的音频波形，使其能够产生逼真的，尽管非结构化的音乐。在本文中，我们提出了一种将这两种方法相结合的自动音乐生成方法，以创建结构化，逼真的音乐作品。我们考虑一个长期短期记忆网络来学习不同风格音乐的旋律结构，然后使用这个模型中独特的符号世代作为基于WaveNet的原始音频发生器的调节输入，创建一个自动，新颖的音乐模型。然后我们通过展示这项工作的结果来评估这种方法。

##### URL
[http://arxiv.org/abs/1806.09905](http://arxiv.org/abs/1806.09905)

##### PDF
[http://arxiv.org/pdf/1806.09905](http://arxiv.org/pdf/1806.09905)

