---
layout: post
title: "Video Fill In the Blank using LR/RL LSTMs with Spatial-Temporal Attentions"
date: 2017-04-15 21:13:41
categories: arXiv_CV
tags: arXiv_CV Attention RNN
author: Amir Mazaheri, Dong Zhang, Mubarak Shah
mathjax: true
---

* content
{:toc}

##### Abstract
Given a video and a description sentence with one missing word (we call it the "source sentence"), Video-Fill-In-the-Blank (VFIB) problem is to find the missing word automatically. The contextual information of the sentence, as well as visual cues from the video, are important to infer the missing word accurately. Since the source sentence is broken into two fragments: the sentence's left fragment (before the blank) and the sentence's right fragment (after the blank), traditional Recurrent Neural Networks cannot encode this structure accurately because of many possible variations of the missing word in terms of the location and type of the word in the source sentence. For example, a missing word can be the first word or be in the middle of the sentence and it can be a verb or an adjective. In this paper, we propose a framework to tackle the textual encoding: Two separate LSTMs (the LR and RL LSTMs) are employed to encode the left and right sentence fragments and a novel structure is introduced to combine each fragment with an "external memory" corresponding the opposite fragments. For the visual encoding, end-to-end spatial and temporal attention models are employed to select discriminative visual representations to find the missing word. In the experiments, we demonstrate the superior performance of the proposed method on challenging VFIB problem. Furthermore, we introduce an extended and more generalized version of VFIB, which is not limited to a single blank. Our experiments indicate the generalization capability of our method in dealing with such more realistic scenarios.

##### Abstract (translated by Google)
给出一个视频和一个带有一个缺失词的描述句子（我们称之为“源语句”），视频填充空白（VFIB）问题是自动找到缺失的词。句子的上下文信息以及来自视频的视觉提示对于精确地推断丢失的单词很重要。由于源句子被分成两个片段：句子的左边片段（在空白之前）和句子的右边片段（在空白之后），传统的递归神经网络不能准确地对这个结构进行编码，因为丢失的单词有许多可能的变化源句子中单词的位置和类型。例如，一个缺失的单词可以是第一个单词或者在句子的中间，它可以是动词或形容词。在本文中，我们提出了一个解决文本编码的框架：使用两个单独的LSTM（LR和RL LSTM）来编码左和右句子片段，并引入一种新的结构来将每个片段与“外部存储器”对应相反的片段。对于视觉编码，采用端到端的空间和时间关注模型来选择有区别的视觉表示来找到丢失的单词。在实验中，我们证明了所提出的方法在挑战VFIB问题上的优越性能。此外，我们介绍了一个扩展和更广义的VFIB版本，不限于一个空白。我们的实验表明了我们的方法在处理这种更真实的情况下的泛化能力。

##### URL
[https://arxiv.org/abs/1704.04689](https://arxiv.org/abs/1704.04689)

##### PDF
[https://arxiv.org/pdf/1704.04689](https://arxiv.org/pdf/1704.04689)

