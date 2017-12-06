---
layout: post
title: 'Sequence to Sequence -- Video to Text'
date: 2017-12-06 09:15:36
categories: arXiv_CV
tags: arXiv_CV Image_Caption Video_Caption Caption RNN
author: Subhashini Venugopalan, Marcus Rohrbach, Jeff Donahue, Raymond Mooney, Trevor Darrell, Kate Saenko
---

* content
{:toc}

##### Abstract
Real-world videos often have complex dynamics; and methods for generating open-domain video descriptions should be sensitive to temporal structure and allow both input (sequence of frames) and output (sequence of words) of variable length. To approach this problem, we propose a novel end-to-end sequence-to-sequence model to generate captions for videos. For this we exploit recurrent neural networks, specifically LSTMs, which have demonstrated state-of-the-art performance in image caption generation. Our LSTM model is trained on video-sentence pairs and learns to associate a sequence of video frames to a sequence of words in order to generate a description of the event in the video clip. Our model naturally is able to learn the temporal structure of the sequence of frames as well as the sequence model of the generated sentences, i.e. a language model. We evaluate several variants of our model that exploit different visual features on a standard set of YouTube videos and two movie description datasets (M-VAD and MPII-MD).

##### Abstract (translated by Google)
真实世界的视频通常具有复杂的动态;并且用于生成开域视频描述的方法应该对时间结构敏感，并允许可变长度的输入（帧的序列）和输出（字的序列）。为了解决这个问题，我们提出了一个新颖的端到端序列到序列模型来生成视频的标题。为此，我们利用循环神经网络，特别是LSTM，它们在图像标题生成中展示了最先进的性能。我们的LSTM模型在视频 - 句子对上进行训练，并学习将视频帧序列与单词序列相关联，以生成视频片段中事件的描述。我们的模型自然能够学习帧序列的时间结构以及生成的句子的序列模型，即语言模型。我们评估了我们模型的几个变体，它们在标准的YouTube视频集和两个电影描述数据集（M-VAD和MPII-MD）上利用不同的视觉特征。

##### URL
[https://arxiv.org/abs/1505.00487](https://arxiv.org/abs/1505.00487)

