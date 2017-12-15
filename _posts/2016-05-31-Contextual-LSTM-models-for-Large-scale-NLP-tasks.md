---
layout: post
title: "Contextual LSTM models for Large scale NLP tasks"
date: 2016-05-31 17:19:09
categories: arXiv_SD
tags: arXiv_SD RNN Prediction
author: Shalini Ghosh, Oriol Vinyals, Brian Strope, Scott Roy, Tom Dean, Larry Heck
mathjax: true
---

* content
{:toc}

##### Abstract
Documents exhibit sequential structure at multiple levels of abstraction (e.g., sentences, paragraphs, sections). These abstractions constitute a natural hierarchy for representing the context in which to infer the meaning of words and larger fragments of text. In this paper, we present CLSTM (Contextual LSTM), an extension of the recurrent neural network LSTM (Long-Short Term Memory) model, where we incorporate contextual features (e.g., topics) into the model. We evaluate CLSTM on three specific NLP tasks: word prediction, next sentence selection, and sentence topic prediction. Results from experiments run on two corpora, English documents in Wikipedia and a subset of articles from a recent snapshot of English Google News, indicate that using both words and topics as features improves performance of the CLSTM models over baseline LSTM models for these tasks. For example on the next sentence selection task, we get relative accuracy improvements of 21% for the Wikipedia dataset and 18% for the Google News dataset. This clearly demonstrates the significant benefit of using context appropriately in natural language (NL) tasks. This has implications for a wide variety of NL applications like question answering, sentence completion, paraphrase generation, and next utterance prediction in dialog systems.

##### Abstract (translated by Google)
文档在多个抽象级别（例如，句子，段落，部分）中显示顺序结构。这些抽象构成了一个自然的层次结构，用来表示文本的意义和更大的文本片断的推理环境。在本文中，我们提出了CLSTM（上下文LSTM），这是递归神经网络LSTM（长 - 短期记忆）模型的扩展，其中我们将上下文特征（例如主题）纳入到模型中。我们评估CLSTM三个特定的NLP任务：单词预测，下一句话选择和句子话题预测。在维基百科的两个语料库，英文文档以及最近的英文Google新闻快照中的文章的子集上运行的实验结果表明，使用单词和主题作为特征，可以提高CLSTM模型相对于这些任务的基线LSTM模型的性能。例如，在下一个句子选择任务中，我们获得了维基百科数据集的21％和Google新闻数据集的18％的相对准确度提高。这清楚地表明了在自然语言（NL）任务中适当使用上下文的重大好处。这对于各种各样的NL应用都是有意义的，例如对话系统中的问题解答，句子完成，释义生成和下一个话语预测。

##### URL
[https://arxiv.org/abs/1602.06291](https://arxiv.org/abs/1602.06291)

##### PDF
[https://arxiv.org/pdf/1602.06291](https://arxiv.org/pdf/1602.06291)

