---
layout: post
title: "Cross-domain Semantic Parsing via Paraphrasing"
date: 2017-07-24 19:35:17
categories: arXiv_CL
tags: arXiv_CL Embedding
author: Yu Su, Xifeng Yan
mathjax: true
---

* content
{:toc}

##### Abstract
Existing studies on semantic parsing mainly focus on the in-domain setting. We formulate cross-domain semantic parsing as a domain adaptation problem: train a semantic parser on some source domains and then adapt it to the target domain. Due to the diversity of logical forms in different domains, this problem presents unique and intriguing challenges. By converting logical forms into canonical utterances in natural language, we reduce semantic parsing to paraphrasing, and develop an attentive sequence-to-sequence paraphrase model that is general and flexible to adapt to different domains. We discover two problems, small micro variance and large macro variance, of pre-trained word embeddings that hinder their direct use in neural networks, and propose standardization techniques as a remedy. On the popular Overnight dataset, which contains eight domains, we show that both cross-domain training and standardized pre-trained word embeddings can bring significant improvement.

##### Abstract (translated by Google)
目前对语义分析的研究主要集中在域内设置。我们将跨域语义解析作为一个领域适应问题来制定：在一些源域上训练一个语义解析器，然后将其适配到目标域。由于不同领域逻辑形式的多样性，这个问题呈现出独特而有趣的挑战。通过将自然语言中的逻辑形式转换为规范的语言，我们将语义解析转化为释义，并开发了一个通用而灵活的适应不同领域的顺序 - 顺序释义模型。我们发现了预先训练的词嵌入阻碍了它们直接用于神经网络的两个问题，即微小方差和宏观方差大，并提出了标准化技术作为补救措施。在流行的夜间数据集，其中包含八个领域，我们表明，跨领域的训练和标准化的预训练词嵌入可以带来显着的改善。

##### URL
[https://arxiv.org/abs/1704.05974](https://arxiv.org/abs/1704.05974)

##### PDF
[https://arxiv.org/pdf/1704.05974](https://arxiv.org/pdf/1704.05974)

