---
layout: post
title: "Gated Word-Character Recurrent Language Model"
date: 2016-10-13 03:26:43
categories: arXiv_CL
tags: arXiv_CL RNN Language_Model
author: Yasumasa Miyamoto, Kyunghyun Cho
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a recurrent neural network language model (RNN-LM) with long short-term memory (LSTM) units that utilizes both character-level and word-level inputs. Our model has a gate that adaptively finds the optimal mixture of the character-level and word-level inputs. The gate creates the final vector representation of a word by combining two distinct representations of the word. The character-level inputs are converted into vector representations of words using a bidirectional LSTM. The word-level inputs are projected into another high-dimensional space by a word lookup table. The final vector representations of words are used in the LSTM language model which predicts the next word given all the preceding words. Our model with the gating mechanism effectively utilizes the character-level inputs for rare and out-of-vocabulary words and outperforms word-level language models on several English corpora.

##### Abstract (translated by Google)
我们引入具有长期短期记忆（LSTM）单元的递归神经网络语言模型（RNN-LM），其使用字符级和字级输入。我们的模型具有自适应地找到字符级和字级输入的最佳混合的门。门通过组合词的两个不同表示来创建词的最终矢量表示。使用双向LSTM将字符级输入转换为字的向量表示。字级输入通过字查找表投影到另一个高维空间。在LSTM语言模型中使用单词的最终矢量表示，其预测在给定所有前面的单词的下一个单词。我们的模型与门控机制有效地利用字符级输入的罕见词汇和超出单词，并胜过英语语料库的几个英语语言模型。

##### URL
[https://arxiv.org/abs/1606.01700](https://arxiv.org/abs/1606.01700)

##### PDF
[https://arxiv.org/pdf/1606.01700](https://arxiv.org/pdf/1606.01700)

