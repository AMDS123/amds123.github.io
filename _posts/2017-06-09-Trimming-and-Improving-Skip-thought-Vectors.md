---
layout: post
title: "Trimming and Improving Skip-thought Vectors"
date: 2017-06-09 22:44:31
categories: arXiv_CL
tags: arXiv_CL Text_Classification Embedding Classification Detection
author: Shuai Tang, Hailin Jin, Chen Fang, Zhaowen Wang, Virginia R. de Sa
mathjax: true
---

* content
{:toc}

##### Abstract
The skip-thought model has been proven to be effective at learning sentence representations and capturing sentence semantics. In this paper, we propose a suite of techniques to trim and improve it. First, we validate a hypothesis that, given a current sentence, inferring the previous and inferring the next sentence provide similar supervision power, therefore only one decoder for predicting the next sentence is preserved in our trimmed skip-thought model. Second, we present a connection layer between encoder and decoder to help the model to generalize better on semantic relatedness tasks. Third, we found that a good word embedding initialization is also essential for learning better sentence representations. We train our model unsupervised on a large corpus with contiguous sentences, and then evaluate the trained model on 7 supervised tasks, which includes semantic relatedness, paraphrase detection, and text classification benchmarks. We empirically show that, our proposed model is a faster, lighter-weight and equally powerful alternative to the original skip-thought model.

##### Abstract (translated by Google)
跳过思维模式已被证明是有效的学习句子表示和捕捉句子语义。在本文中，我们提出了一整套技术来修整和改进它。首先，我们验证一个假设：在给定当前句子的情况下，推断前一个句子并推断下一个句子提供相似的监督能力，因此在我们修剪的跳跃思想模型中只保留一个用于预测下一个句子的解码器。其次，在编码器和解码器之间提出了一个连接层，以帮助模型更好地推广语义相关性任务。第三，我们发现一个好的词嵌入初始化对学习更好的句子表示也是必不可少的。我们在一个连续句子的大型语料库上对我们的模型进行无监督训练，然后对7个监督任务的训练模型进行评估，包括语义相关性，释义检测和文本分类基准。我们经验地表明，我们提出的模型是一个更快，更轻，同样强大的替代原来的跳跃思想模型。

##### URL
[https://arxiv.org/abs/1706.03148](https://arxiv.org/abs/1706.03148)

##### PDF
[https://arxiv.org/pdf/1706.03148](https://arxiv.org/pdf/1706.03148)

