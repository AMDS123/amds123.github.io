---
layout: post
title: "Learning to generate one-sentence biographies from Wikidata"
date: 2017-02-21 01:30:59
categories: arXiv_SD
tags: arXiv_SD Knowledge Attention
author: Andrew Chisholm, Will Radford, Ben Hachey
mathjax: true
---

* content
{:toc}

##### Abstract
We investigate the generation of one-sentence Wikipedia biographies from facts derived from Wikidata slot-value pairs. We train a recurrent neural network sequence-to-sequence model with attention to select facts and generate textual summaries. Our model incorporates a novel secondary objective that helps ensure it generates sentences that contain the input facts. The model achieves a BLEU score of 41, improving significantly upon the vanilla sequence-to-sequence model and scoring roughly twice that of a simple template baseline. Human preference evaluation suggests the model is nearly as good as the Wikipedia reference. Manual analysis explores content selection, suggesting the model can trade the ability to infer knowledge against the risk of hallucinating incorrect information.

##### Abstract (translated by Google)
我们调查维基百科传记中的维基百科个人简历的来源。我们训练循环神经网络序列 - 序列模型，注意选择事实并生成文本摘要。我们的模型结合了一个新颖的次要目标，有助于确保生成包含输入事实的句子。该模型实现了41的BLEU得分，在香草序列 - 序列模型上显着改善，并且大致评分了简单模板基线的两倍。人类偏好评估表明，该模型几乎与维基百科参考文献一样好。手工分析探讨了内容选择，表明该模型可以将知识推断的能力与幻觉不正确信息的风险进行交易。

##### URL
[https://arxiv.org/abs/1702.06235](https://arxiv.org/abs/1702.06235)

##### PDF
[https://arxiv.org/pdf/1702.06235](https://arxiv.org/pdf/1702.06235)

