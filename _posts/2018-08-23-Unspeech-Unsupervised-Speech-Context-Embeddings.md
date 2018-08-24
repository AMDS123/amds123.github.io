---
layout: post
title: "Unspeech: Unsupervised Speech Context Embeddings"
date: 2018-08-23 10:33:44
categories: arXiv_CL
tags: arXiv_CL Embedding CNN
author: Benjamin Milde, Chris Biemann
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce "Unspeech" embeddings, which are based on unsupervised learning of context feature representations for spoken language. The embeddings were trained on up to 9500 hours of crawled English speech data without transcriptions or speaker information, by using a straightforward learning objective based on context and non-context discrimination with negative sampling. We use a Siamese convolutional neural network architecture to train Unspeech embeddings and evaluate them on speaker comparison, utterance clustering and as a context feature in TDNN-HMM acoustic models trained on TED-LIUM, comparing it to i-vector baselines. Particularly decoding out-of-domain speech data from the recently released Common Voice corpus shows consistent WER reductions. We release our source code and pre-trained Unspeech models under a permissive open source license.

##### Abstract (translated by Google)
我们介绍了“非语言”嵌入，它基于对口语的上下文特征表示的无监督学习。通过使用基于上下文的直接学习目标和使用负面采样的非上下文区分，对嵌入式文件进行长达9500小时的爬行英语语音数据的训练而无需转录或说话者信息。我们使用Siamese卷积神经网络架构来训练非语言嵌入，并在说话者比较，话语聚类和作为TED-LIUM训练的TDNN-HMM声学模型中的上下文特征进行评估，将其与i向量基线进行比较。特别地，解码来自最近发布的公共语音语料库的域外语音数据显示出一致的WER减少。我们在宽松的开源许可下发布我们的源代码和预先培训的Unspeech模型。

##### URL
[http://arxiv.org/abs/1804.06775](http://arxiv.org/abs/1804.06775)

##### PDF
[http://arxiv.org/pdf/1804.06775](http://arxiv.org/pdf/1804.06775)

