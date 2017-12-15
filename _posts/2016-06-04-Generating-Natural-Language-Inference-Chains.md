---
layout: post
title: "Generating Natural Language Inference Chains"
date: 2016-06-04 18:34:51
categories: arXiv_CL
tags: arXiv_CL Attention Inference RNN
author: Vladyslav Kolesnyk, Tim Rocktäschel, Sebastian Riedel
mathjax: true
---

* content
{:toc}

##### Abstract
The ability to reason with natural language is a fundamental prerequisite for many NLP tasks such as information extraction, machine translation and question answering. To quantify this ability, systems are commonly tested whether they can recognize textual entailment, i.e., whether one sentence can be inferred from another one. However, in most NLP applications only single source sentences instead of sentence pairs are available. Hence, we propose a new task that measures how well a model can generate an entailed sentence from a source sentence. We take entailment-pairs of the Stanford Natural Language Inference corpus and train an LSTM with attention. On a manually annotated test set we found that 82% of generated sentences are correct, an improvement of 10.3% over an LSTM baseline. A qualitative analysis shows that this model is not only capable of shortening input sentences, but also inferring new statements via paraphrasing and phrase entailment. We then apply this model recursively to input-output pairs, thereby generating natural language inference chains that can be used to automatically construct an entailment graph from source sentences. Finally, by swapping source and target sentences we can also train a model that given an input sentence invents additional information to generate a new sentence.

##### Abstract (translated by Google)
使用自然语言进行推理的能力是许多NLP任务（如信息提取，机器翻译和问答）的基本前提条件。为了量化这种能力，系统通常被测试是否能够识别文本含义，即是否可以从另一个句子推断出一个句子。然而，在大多数NLP应用程序中，只有单个源语句而不是句对是可用的。因此，我们提出一个新的任务来衡量一个模型如何能够从一个源句子中产生一个需要的句子。我们采用斯坦福自然语言推理语料库的蕴涵对，并且注意训练LSTM。在手动注释的测试集中，我们发现82％的生成句子是正确的，比LSTM基线提高了10.3％。定性分析表明，该模型不仅能够缩短输入句子，而且能够通过释义和短语引出新的陈述。然后，我们将这个模型递归地应用到输入 - 输出对上，从而生成自然语言推理链，可以用来从源语句自动构造蕴含图。最后，通过交换源句子和目标句子，我们还可以训练一个模型，给定一个输入句子发明额外的信息来产生一个新的句子。

##### URL
[https://arxiv.org/abs/1606.01404](https://arxiv.org/abs/1606.01404)

##### PDF
[https://arxiv.org/pdf/1606.01404](https://arxiv.org/pdf/1606.01404)

