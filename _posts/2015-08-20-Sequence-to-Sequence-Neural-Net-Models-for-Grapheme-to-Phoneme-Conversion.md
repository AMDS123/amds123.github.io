---
layout: post
title: "Sequence-to-Sequence Neural Net Models for Grapheme-to-Phoneme Conversion"
date: 2015-08-20 06:27:07
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption RNN Language_Model
author: Kaisheng Yao, Geoffrey Zweig
mathjax: true
---

* content
{:toc}

##### Abstract
Sequence-to-sequence translation methods based on generation with a side-conditioned language model have recently shown promising results in several tasks. In machine translation, models conditioned on source side words have been used to produce target-language text, and in image captioning, models conditioned images have been used to generate caption text. Past work with this approach has focused on large vocabulary tasks, and measured quality in terms of BLEU. In this paper, we explore the applicability of such models to the qualitatively different grapheme-to-phoneme task. Here, the input and output side vocabularies are small, plain n-gram models do well, and credit is only given when the output is exactly correct. We find that the simple side-conditioned generation approach is able to rival the state-of-the-art, and we are able to significantly advance the stat-of-the-art with bi-directional long short-term memory (LSTM) neural networks that use the same alignment information that is used in conventional approaches.

##### Abstract (translated by Google)
基于侧边语言模型生成的序列到序列的翻译方法最近在几个任务中显示出有希望的结果。在机器翻译中，以源语词汇为条件的模型已被用于生成目标语言文本，而在图像字幕中，模型条件图像已被用于生成字幕文本。过去使用这种方法的工作集中在大量的词汇任务上，并以BLEU来衡量质量。在本文中，我们探讨了这种模型对定性不同的字形音素任务的适用性。在这里，输入和输出方面的词汇是很小的，简单的n元模型做的很好，而且只有当输出是完全正确的时候才能得到信用。我们发现，简单的边界条件生成方法能够与最新的技术相匹敌，并且我们能够通过双向长时间短期记忆（LSTM）来显着提高最新的技术水平，神经网络使用在传统方法中使用的相同的对准信息。

##### URL
[https://arxiv.org/abs/1506.00196](https://arxiv.org/abs/1506.00196)

##### PDF
[https://arxiv.org/pdf/1506.00196](https://arxiv.org/pdf/1506.00196)

