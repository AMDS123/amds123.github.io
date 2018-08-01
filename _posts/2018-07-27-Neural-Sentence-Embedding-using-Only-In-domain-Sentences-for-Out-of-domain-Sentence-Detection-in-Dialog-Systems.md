---
layout: post
title: "Neural Sentence Embedding using Only In-domain Sentences for Out-of-domain Sentence Detection in Dialog Systems"
date: 2018-07-27 15:31:15
categories: arXiv_AI
tags: arXiv_AI Embedding Detection
author: Seonghan Ryu, Seokhwan Kim, Junhwi Choi, Hwanjo Yu, Gary Geunbae Lee
mathjax: true
---

* content
{:toc}

##### Abstract
To ensure satisfactory user experience, dialog systems must be able to determine whether an input sentence is in-domain (ID) or out-of-domain (OOD). We assume that only ID sentences are available as training data because collecting enough OOD sentences in an unbiased way is a laborious and time-consuming job. This paper proposes a novel neural sentence embedding method that represents sentences in a low-dimensional continuous vector space that emphasizes aspects that distinguish ID cases from OOD cases. We first used a large set of unlabeled text to pre-train word representations that are used to initialize neural sentence embedding. Then we used domain-category analysis as an auxiliary task to train neural sentence embedding for OOD sentence detection. After the sentence representations were learned, we used them to train an autoencoder aimed at OOD sentence detection. We evaluated our method by experimentally comparing it to the state-of-the-art methods in an eight-domain dialog system; our proposed method achieved the highest accuracy in all tests.

##### Abstract (translated by Google)
为了确保令人满意的用户体验，对话系统必须能够确定输入句子是域内（ID）还是域外（OOD）。我们假设只有ID句子可用作训练数据，因为以无偏见的方式收集足够的OOD句子是一项费时费力的工作。本文提出了一种新颖的神经句嵌入方法，该方法在低维连续向量空间中表示句子，强调区分ID案例和OOD案例的方面。我们首先使用大量未标记的文本来预训练用于初始化神经句嵌入的单词表示。然后我们使用领域类别分析作为辅助任务来训练用于OOD语句检测的神经句嵌入。在学习了句子表示之后，我们用它们来训练一个针对OOD句子检测的自动编码器。我们通过实验将它与八域对话系统中最先进的方法进行比较来评估我们的方法;我们提出的方法在所有测试中都达到了最高精度。

##### URL
[http://arxiv.org/abs/1807.11567](http://arxiv.org/abs/1807.11567)

##### PDF
[http://arxiv.org/pdf/1807.11567](http://arxiv.org/pdf/1807.11567)

