---
layout: post
title: "Improving Neural Question Generation using Answer Separation"
date: 2018-09-07 10:35:42
categories: arXiv_CL
tags: arXiv_CL
author: Yanghoon Kim, Hwanhee Lee, Joongbo Shin, Kyomin Jung
mathjax: true
---

* content
{:toc}

##### Abstract
Neural question generation (NQG) is the task of generating a question from a given passage with deep neural networks. Previous NQG models suffer from a problem that a significant proportion of the generated questions include words in the question target, resulting in the generation of unintended questions. In this paper, we propose answer-separated seq2seq, which better utilizes the information from both the passage and the target answer. By replacing the target answer in the original passage with a special token, our model learns to identify which interrogative word should be used. We also propose a new module termed keyword-net, which helps the model better capture the key information in the target answer and generate an appropriate question. Experimental results demonstrate that our answer separation method significantly reduces the number of improper questions which include answers. Consequently, our model significantly outperforms previous state-of-the-art NQG models.

##### Abstract (translated by Google)
神经问题生成（NQG）是使用深度神经网络从给定通道生成问题的任务。以前的NQG模型遇到的问题是，生成的问题中有很大一部分包含问题目标中的单词，导致产生意外问题。在本文中，我们提出了答案分离的seq2seq，它更好地利用了段落和目标答案的信息。通过用特殊标记替换原始段落中的目标答案，我们的模型学会识别应该使用哪个疑问词。我们还提出了一个名为keyword-net的新模块，它有助于模型更好地捕获目标答案中的关键信息并生成适当的问题。实验结果表明，我们的答案分离方法显着减少了包含答案的不正确问题的数量。因此，我们的模型明显优于以前最先进的NQG模型。

##### URL
[https://arxiv.org/abs/1809.02393](https://arxiv.org/abs/1809.02393)

##### PDF
[https://arxiv.org/pdf/1809.02393](https://arxiv.org/pdf/1809.02393)

