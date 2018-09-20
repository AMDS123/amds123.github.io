---
layout: post
title: "Latent Topic Conversational Models"
date: 2018-09-19 08:58:23
categories: arXiv_CL
tags: arXiv_CL
author: Tsung-Hsien Wen, Minh-Thang Luong
mathjax: true
---

* content
{:toc}

##### Abstract
Latent variable models have been a preferred choice in conversational modeling compared to sequence-to-sequence (seq2seq) models which tend to generate generic and repetitive responses. Despite so, training latent variable models remains to be difficult. In this paper, we propose Latent Topic Conversational Model (LTCM) which augments seq2seq with a neural latent topic component to better guide response generation and make training easier. The neural topic component encodes information from the source sentence to build a global "topic" distribution over words, which is then consulted by the seq2seq model at each generation step. We study in details how the latent representation is learnt in both the vanilla model and LTCM. Our extensive experiments contribute to better understanding and training of conditional latent models for languages. Our results show that by sampling from the learnt latent representations, LTCM can generate diverse and interesting responses. In a subjective human evaluation, the judges also confirm that LTCM is the overall preferred option.

##### Abstract (translated by Google)
与序列到序列（seq2seq）模型相比，潜变量模型一直是会话建模的首选，这些模型倾向于生成通用和重复响应。尽管如此，训练隐变量模型仍然很困难。在本文中，我们提出潜在主题会话模型（LTCM），它使用神经潜在主题组件增加seq2seq，以更好地指导响应生成并使培训更容易。神经主题组件对来自源句子的信息进行编码，以在单词上构建全局“主题”分布，然后在每个生成步骤由seq2seq模型进行查询。我们详细研究了如何在香草模型和LTCM中学习潜在表示。我们广泛的实验有助于更好地理解和训练语言的条件潜在模型。我们的研究结果表明，通过从学到的潜在表征中抽样，LTCM可以产生各种有趣的响应。在主观的人类评估中，评委还确认LTCM是首选的选择。

##### URL
[http://arxiv.org/abs/1809.07070](http://arxiv.org/abs/1809.07070)

##### PDF
[http://arxiv.org/pdf/1809.07070](http://arxiv.org/pdf/1809.07070)

