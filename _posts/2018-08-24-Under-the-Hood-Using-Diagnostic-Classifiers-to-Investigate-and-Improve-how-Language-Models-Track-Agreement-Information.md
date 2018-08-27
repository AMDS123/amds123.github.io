---
layout: post
title: "Under the Hood: Using Diagnostic Classifiers to Investigate and Improve how Language Models Track Agreement Information"
date: 2018-08-24 10:29:45
categories: arXiv_AI
tags: arXiv_AI Knowledge RNN Language_Model
author: Mario Giulianelli, Jack Harding, Florian Mohnert, Dieuwke Hupkes, Willem Zuidema
mathjax: true
---

* content
{:toc}

##### Abstract
How do neural language models keep track of number agreement between subject and verb? We show that `diagnostic classifiers', trained to predict number from the internal states of a language model, provide a detailed understanding of how, when, and where this information is represented. Moreover, they give us insight into when and where number information is corrupted in cases where the language model ends up making agreement errors. To demonstrate the causal role played by the representations we find, we then use agreement information to influence the course of the LSTM during the processing of difficult sentences. Results from such an intervention reveal a large increase in the language model's accuracy. Together, these results show that diagnostic classifiers give us an unrivalled detailed look into the representation of linguistic information in neural models, and demonstrate that this knowledge can be used to improve their performance.

##### Abstract (translated by Google)
神经语言模型如何跟踪主语和动词之间的数字一致性？我们证明，“诊断分类器”经过训练可以从语言模型的内部状态预测数字，可以详细了解这些信息的表示方式，时间和地点。此外，它们让我们深入了解在语言模型最终导致协议错误的情况下，数字信息何时何地被破坏。为了证明我们发现的表示所起的因果作用，我们然后使用协议信息来影响LSTM在处理难句时的过程。这种干预的结果表明语言模型的准确性大大增加。总之，这些结果表明，诊断分类器为我们提供了无与伦比的详细研究神经模型中语言信息的表示，并证明这些知识可用于改善其性能。

##### URL
[http://arxiv.org/abs/1808.08079](http://arxiv.org/abs/1808.08079)

##### PDF
[http://arxiv.org/pdf/1808.08079](http://arxiv.org/pdf/1808.08079)

