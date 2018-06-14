---
layout: post
title: "Generative Neural Machine Translation"
date: 2018-06-13 16:35:32
categories: arXiv_CL
tags: arXiv_CL NMT
author: Harshil Shah, David Barber
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce Generative Neural Machine Translation (GNMT), a latent variable architecture which is designed to model the semantics of the source and target sentences. We modify an encoder-decoder translation model by adding a latent variable as a language agnostic representation which is encouraged to learn the meaning of the sentence. GNMT achieves competitive BLEU scores on pure translation tasks, and is superior when there are missing words in the source sentence. We augment the model to facilitate multilingual translation and semi-supervised learning without adding parameters. This framework significantly reduces overfitting when there is limited paired data available, and is effective for translating between pairs of languages not seen during training.

##### Abstract (translated by Google)
我们引入了生成式神经机器翻译（GNMT），这是一种潜在变量架构，它被设计用来模拟源语句和目标语句的语义。我们通过添加一个潜在变量作为语言不可知表示来修改编码器 - 译码器翻译模型，鼓励他们学习语句的含义。 GNMT在纯翻译任务上取得了极具竞争力的BLEU成绩，并且在源句子中缺少单词的情况下优于BLEU成绩。我们增加了模型，以促进多语言翻译和半监督学习，而无需添加参数。当有限的配对数据可用时，该框架可显着减少过度拟合，并且有效地用于在培训期间看不到的语言对之间进行翻译。

##### URL
[https://arxiv.org/abs/1806.05138](https://arxiv.org/abs/1806.05138)

##### PDF
[https://arxiv.org/pdf/1806.05138](https://arxiv.org/pdf/1806.05138)

