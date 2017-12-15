---
layout: post
title: "Unsupervised Discovery of Linguistic Structure Including Two-level Acoustic Patterns Using Three Cascaded Stages of Iterative Optimization"
date: 2015-09-07 22:23:01
categories: arXiv_CL
tags: arXiv_CL Knowledge Optimization Language_Model Detection
author: Cheng-Tao Chung, Chun-an Chan, Lin-shan Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Techniques for unsupervised discovery of acoustic patterns are getting increasingly attractive, because huge quantities of speech data are becoming available but manual annotations remain hard to acquire. In this paper, we propose an approach for unsupervised discovery of linguistic structure for the target spoken language given raw speech data. This linguistic structure includes two-level (subword-like and word-like) acoustic patterns, the lexicon of word-like patterns in terms of subword-like patterns and the N-gram language model based on word-like patterns. All patterns, models, and parameters can be automatically learned from the unlabelled speech corpus. This is achieved by an initialization step followed by three cascaded stages for acoustic, linguistic, and lexical iterative optimization. The lexicon of word-like patterns defines allowed consecutive sequence of HMMs for subword-like patterns. In each iteration, model training and decoding produces updated labels from which the lexicon and HMMs can be further updated. In this way, model parameters and decoded labels are respectively optimized in each iteration, and the knowledge about the linguistic structure is learned gradually layer after layer. The proposed approach was tested in preliminary experiments on a corpus of Mandarin broadcast news, including a task of spoken term detection with performance compared to a parallel test using models trained in a supervised way. Results show that the proposed system not only yields reasonable performance on its own, but is also complimentary to existing large vocabulary ASR systems.

##### Abstract (translated by Google)
无监督地发现声音模式的技术越来越有吸引力，因为大量的语音数据变得可用，但手动注释仍然难以获得。在本文中，我们提出了一种无监督地发现在给定原始语音数据的情况下针对目标口语的语言结构的方法。这种语言结构包括两层次（类似于子词和单词）的声学模式，根据子词类型的词类模式的词典和基于词类模式的N-gram语言模型。所有模式，模型和参数都可以从未标注的语料库中自动学习。这是通过一个初始化步骤，然后是三个级联级进行声学，语言和词汇迭代优化。词类模式的词典定义允许的连续序列的HMMs用于子字样模式。在每次迭代中，模型训练和解码产生更新的标签，从中可以进一步更新词典和HMM。这样，每次迭代分别对模型参数和解码标签进行优化，逐层学习语言结构的知识。所提出的方法在普通话广播新闻语料库的初步实验中进行了测试，包括与使用受监督方式训练的模型的平行测试相比，口头词语检测的任务性能。结果表明，所提出的系统不仅能够自行产生合理的性能，而且对现有的大型词汇ASR系统也是有益的。

##### URL
[https://arxiv.org/abs/1509.02208](https://arxiv.org/abs/1509.02208)

##### PDF
[https://arxiv.org/pdf/1509.02208](https://arxiv.org/pdf/1509.02208)

