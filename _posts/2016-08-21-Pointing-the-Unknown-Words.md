---
layout: post
title: "Pointing the Unknown Words"
date: 2016-08-21 20:03:39
categories: arXiv_SD
tags: arXiv_SD Attention Summarization Deep_Learning Language_Model
author: Caglar Gulcehre, Sungjin Ahn, Ramesh Nallapati, Bowen Zhou, Yoshua Bengio
mathjax: true
---

* content
{:toc}

##### Abstract
The problem of rare and unknown words is an important issue that can potentially influence the performance of many NLP systems, including both the traditional count-based and the deep learning models. We propose a novel way to deal with the rare and unseen words for the neural network models using attention. Our model uses two softmax layers in order to predict the next word in conditional language models: one predicts the location of a word in the source sentence, and the other predicts a word in the shortlist vocabulary. At each time-step, the decision of which softmax layer to use choose adaptively made by an MLP which is conditioned on the context.~We motivate our work from a psychological evidence that humans naturally have a tendency to point towards objects in the context or the environment when the name of an object is not known.~We observe improvements on two tasks, neural machine translation on the Europarl English to French parallel corpora and text summarization on the Gigaword dataset using our proposed model.

##### Abstract (translated by Google)
罕见和未知单词的问题是潜在影响许多NLP系统的性能的重要问题，包括传统的基于计数的模型和深度学习模型。我们提出了一种新颖的方法来处理神经网络模型中罕见的和看不见的词语。我们的模型使用两个softmax层来预测条件语言模型中的下一个单词：一个预测源句子中单词的位置，另一个预测短名单词汇表中的单词。在每一个时间步，决定使用哪一个softmax层是由MLP自适应选择的，这个MLP是以上下文为条件的。我们从一个心理学的证据中激发我们的工作，即人类自然地倾向于指向上下文中的对象，我们注意到两个任务的改进：Europarl英语到法语平行语料库的神经机器翻译和使用我们提出的模型的Gigaword数据集的文本总结。

##### URL
[https://arxiv.org/abs/1603.08148](https://arxiv.org/abs/1603.08148)

##### PDF
[https://arxiv.org/pdf/1603.08148](https://arxiv.org/pdf/1603.08148)

