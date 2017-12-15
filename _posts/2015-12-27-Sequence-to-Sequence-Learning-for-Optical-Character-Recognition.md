---
layout: post
title: "Sequence to Sequence Learning for Optical Character Recognition"
date: 2015-12-27 13:55:02
categories: arXiv_CV
tags: arXiv_CV OCR Segmentation Embedding RNN Classification Prediction Quantitative Recognition
author: Devendra Kumar Sahu, Mohak Sukhwani
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an end-to-end recurrent encoder-decoder based sequence learning approach for printed text Optical Character Recognition (OCR). In contrast to present day existing state-of-art OCR solution which uses connectionist temporal classification (CTC) output layer, our approach makes minimalistic assumptions on the structure and length of the sequence. We use a two step encoder-decoder approach -- (a) A recurrent encoder reads a variable length printed text word image and encodes it to a fixed dimensional embedding. (b) This fixed dimensional embedding is subsequently comprehended by decoder structure which converts it into a variable length text output. Our architecture gives competitive performance relative to connectionist temporal classification (CTC) output layer while being executed in more natural settings. The learnt deep word image embedding from encoder can be used for printed text based retrieval systems. The expressive fixed dimensional embedding for any variable length input expedites the task of retrieval and makes it more efficient which is not possible with other recurrent neural network architectures. We empirically investigate the expressiveness and the learnability of long short term memory (LSTMs) in the sequence to sequence learning regime by training our network for prediction tasks in segmentation free printed text OCR. The utility of the proposed architecture for printed text is demonstrated by quantitative and qualitative evaluation of two tasks -- word prediction and retrieval.

##### Abstract (translated by Google)
我们提出了一种基于端到端循环编码解码器的序列学习方法，用于打印文本光学字符识别（OCR）。与现有的采用连接主义时间分类（CTC）输出层的现代最先进的OCR解决方案相比，我们的方法对序列的结构和长度做出了极小的假设。我们使用两步编码器 - 解码器的方法 - （a）一个循环编码器读取一个可变长度的印刷文字图像，并将其编码为一个固定的尺寸嵌入。 （b）这种固定尺寸的嵌入随后被解码器结构所理解，解码器结构将其转换成可变长度的文本输出。我们的体系结构在连接主义时态分类（CTC）输出层相对于更自然的设置执行时具有竞争力。来自编码器的学习深度字图像嵌入可用于基于印刷文本的检索系统。任何可变长度输入的表达固定维嵌入加速了检索的任务，使其更有效，而其他递归神经网络结构是不可能的。我们通过训练我们的网络预测任务在分割自由印刷的文字OCR实验调查长序列短语记忆（LSTMs）序列学习制度的表现力和可学性。所提出的印刷文本结构的效用通过定量和定性评估两个任务 - 单词预测和检索来证明。

##### URL
[https://arxiv.org/abs/1511.04176](https://arxiv.org/abs/1511.04176)

##### PDF
[https://arxiv.org/pdf/1511.04176](https://arxiv.org/pdf/1511.04176)

