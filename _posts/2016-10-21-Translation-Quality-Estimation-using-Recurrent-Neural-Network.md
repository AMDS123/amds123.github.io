---
layout: post
title: "Translation Quality Estimation using Recurrent Neural Network"
date: 2016-10-21 07:01:05
categories: arXiv_CL
tags: arXiv_CL RNN Language_Model
author: Raj Nath Patel, Sasikumar M
mathjax: true
---

* content
{:toc}

##### Abstract
This paper describes our submission to the shared task on word/phrase level Quality Estimation (QE) in the First Conference on Statistical Machine Translation (WMT16). The objective of the shared task was to predict if the given word/phrase is a correct/incorrect (OK/BAD) translation in the given sentence. In this paper, we propose a novel approach for word level Quality Estimation using Recurrent Neural Network Language Model (RNN-LM) architecture. RNN-LMs have been found very effective in different Natural Language Processing (NLP) applications. RNN-LM is mainly used for vector space language modeling for different NLP problems. For this task, we modify the architecture of RNN-LM. The modified system predicts a label (OK/BAD) in the slot rather than predicting the word. The input to the system is a word sequence, similar to the standard RNN-LM. The approach is language independent and requires only the translated text for QE. To estimate the phrase level quality, we use the output of the word level QE system.

##### Abstract (translated by Google)
本文描述了我们提交第一届统计机器翻译大会（WMT16）的单词/短语级别质量评估（QE）的共享任务。共享任务的目标是预测给定的单词/短语在给定的句子中是否是正确的/错误的（OK / BAD）翻译。在本文中，我们提出了一种使用递归神经网络语言模型（RNN-LM）体系结构的词级质量估计的新方法。已经发现RNN-LM在不同的自然语言处理（NLP）应用中非常有效。 RNN-LM主要用于不同NLP问题的向量空间语言建模。为此，我们修改RNN-LM的体系结构。修改的系统预测槽中的标签（OK / BAD），而不是预测该单词。系统的输入是一个字序列，类似于标准的RNN-LM。这种方法是独立于语言的，只需要QE的翻译文本。为了估计词组级别的质量，我们使用词级QE系统的输出。

##### URL
[https://arxiv.org/abs/1610.04841](https://arxiv.org/abs/1610.04841)

##### PDF
[https://arxiv.org/pdf/1610.04841](https://arxiv.org/pdf/1610.04841)

