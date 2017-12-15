---
layout: post
title: "Chinese Song Iambics Generation with Neural Attention-based Model"
date: 2016-06-21 20:21:32
categories: arXiv_CL
tags: arXiv_CL Attention RNN Language_Model
author: Qixin Wang, Tianyi Luo, Dong Wang, Chao Xing
mathjax: true
---

* content
{:toc}

##### Abstract
Learning and generating Chinese poems is a charming yet challenging task. Traditional approaches involve various language modeling and machine translation techniques, however, they perform not as well when generating poems with complex pattern constraints, for example Song iambics, a famous type of poems that involve variable-length sentences and strict rhythmic patterns. This paper applies the attention-based sequence-to-sequence model to generate Chinese Song iambics. Specifically, we encode the cue sentences by a bi-directional Long-Short Term Memory (LSTM) model and then predict the entire iambic with the information provided by the encoder, in the form of an attention-based LSTM that can regularize the generation process by the fine structure of the input cues. Several techniques are investigated to improve the model, including global context integration, hybrid style training, character vector initialization and adaptation. Both the automatic and subjective evaluation results show that our model indeed can learn the complex structural and rhythmic patterns of Song iambics, and the generation is rather successful.

##### Abstract (translated by Google)
学习和创造中国诗歌是一个迷人而富有挑战性的任务。传统的方法涉及到各种语言建模和机器翻译技术，但是在生成具有复杂模式约束的诗歌时，表现不如表现得好，例如宋代诗歌（Song Iambics），这是一种着名的诗歌类型，包含可变长度的句子和严格的节奏模式。本文采用基于注意力的序列 - 序列模型来生成中文歌曲。具体来说，我们用双向长短期记忆（LSTM）模型对提示语句进行编码，然后用编码器提供的信息预测整个音节，形式为基于注意力的LSTM，可以规范生成过程通过输入线索的精细结构。研究了几种技术来改进模型，包括全局上下文融合，混合式训练，字符矢量初始化和自适应。自动和主观的评价结果​​都表明，我们的模型确实可以学习到宋代音乐的复杂结构和韵律模式，而且这一代相当成功。

##### URL
[https://arxiv.org/abs/1604.06274](https://arxiv.org/abs/1604.06274)

##### PDF
[https://arxiv.org/pdf/1604.06274](https://arxiv.org/pdf/1604.06274)

