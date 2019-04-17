---
layout: post
title: "Causality Extraction based on Self-Attentive BiLSTM-CRF with Transferred Embeddings"
date: 2019-04-16 12:54:00
categories: arXiv_CL
tags: arXiv_CL Knowledge Attention Embedding RNN Relation
author: Zhaoning Li (1), Qi Li (1), Xiaotian Zou (1), Jiangtao Ren (1) ((1) School of Data and Computer Science, Sun Yat-Sen University, Guangzhou, P.R.China)
mathjax: true
---

* content
{:toc}

##### Abstract
Causality extraction from natural language texts is a challenging open problem in artificial intelligence. Existing methods utilize patterns, constraints, and machine learning techniques to extract causality, heavily depend on domain knowledge and require considerable human efforts and time on feature engineering. In this paper, we formulate causality extraction as a sequence tagging problem based on a novel causality tagging scheme. On this basis, we propose a neural causality extractor with BiLSTM-CRF model as the backbone, named SCIFI (Self-Attentive BiLSTM-CRF with Flair Embeddings), which can directly extract Cause and Effect, without extracting candidate causal pairs and identifying their relations separately. To tackle the problem of data insufficiency, we transfer the contextual string embeddings, also known as Flair embeddings, which trained on a large corpus into our task. Besides, to improve the performance of causality extraction, we introduce the multi-head self-attention mechanism into SCIFI to learn the dependencies between causal words. We evaluate our method on a public dataset, and experimental results demonstrate that our method achieves significant and consistent improvement as compared to other baselines.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.07629](http://arxiv.org/abs/1904.07629)

##### PDF
[http://arxiv.org/pdf/1904.07629](http://arxiv.org/pdf/1904.07629)

