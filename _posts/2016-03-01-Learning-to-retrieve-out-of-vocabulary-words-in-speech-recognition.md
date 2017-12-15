---
layout: post
title: "Learning to retrieve out-of-vocabulary words in speech recognition"
date: 2016-03-01 14:03:44
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Embedding Recognition
author: Imran Sheikh, Irina Illina, Dominique Fohr, Georges Linarès
mathjax: true
---

* content
{:toc}

##### Abstract
Many Proper Names (PNs) are Out-Of-Vocabulary (OOV) words for speech recognition systems used to process diachronic audio data. To help recovery of the PNs missed by the system, relevant OOV PNs can be retrieved out of the many OOVs by exploiting semantic context of the spoken content. In this paper, we propose two neural network models targeted to retrieve OOV PNs relevant to an audio document: (a) Document level Continuous Bag of Words (D-CBOW), (b) Document level Continuous Bag of Weighted Words (D-CBOW2). Both these models take document words as input and learn with an objective to maximise the retrieval of co-occurring OOV PNs. With the D-CBOW2 model we propose a new approach in which the input embedding layer is augmented with a context anchor layer. This layer learns to assign importance to input words and has the ability to capture (task specific) key-words in a bag-of-word neural network model. With experiments on French broadcast news videos we show that these two models outperform the baseline methods based on raw embeddings from LDA, Skip-gram and Paragraph Vectors. Combining the D-CBOW and D-CBOW2 models gives faster convergence during training.

##### Abstract (translated by Google)
许多专有名称（PN）是用于处理历时音频数据的语音识别系统的词汇外（OOV）单词。为了帮助系统错过的PN的恢复，通过利用口头内容的语义上下文，可以从许多OOV中检索相关的OOV PN。在本文中，我们提出了两个神经网络模型，旨在检索与音频文档相关的OOV PN：（a）文档级连续字袋（D-CBOW），（b）文档级连续袋加权字（D-CBOW2 ）。这两种模型都将文档词语作为输入，并以一个目标进行学习，以最大限度地提取共现的OOV PN的检索。在D-CBOW2模型中，我们提出了一种新的方法，其中输入嵌入层用上下文锚层来增强。该层学习重视输入单词，并有能力捕捉（任务特定的）关键词在一个词袋神经网络模型。通过对法国广播新闻视频进行实验，我们发现这两个模型比基于LDA，Skip-gram和Paragraph Vectors中的原始嵌入的基线方法更胜一筹。将D-CBOW和D-CBOW2模型结合起来，可以提高训练过程中的收敛速度。

##### URL
[https://arxiv.org/abs/1511.05389](https://arxiv.org/abs/1511.05389)

##### PDF
[https://arxiv.org/pdf/1511.05389](https://arxiv.org/pdf/1511.05389)

