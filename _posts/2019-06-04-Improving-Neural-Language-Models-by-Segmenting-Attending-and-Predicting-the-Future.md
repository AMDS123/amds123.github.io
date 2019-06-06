---
layout: post
title: "Improving Neural Language Models by Segmenting, Attending, and Predicting the Future"
date: 2019-06-04 19:58:05
categories: arXiv_CL
tags: arXiv_CL Knowledge Segmentation Embedding Language_Model
author: Hongyin Luo, Lan Jiang, Yonatan Belinkov, James Glass
mathjax: true
---

* content
{:toc}

##### Abstract
Common language models typically predict the next word given the context. In this work, we propose a method that improves language modeling by learning to align the given context and the following phrase. The model does not require any linguistic annotation of phrase segmentation. Instead, we define syntactic heights and phrase segmentation rules, enabling the model to automatically induce phrases, recognize their task-specific heads, and generate phrase embeddings in an unsupervised learning manner. Our method can easily be applied to language models with different network architectures since an independent module is used for phrase induction and context-phrase alignment, and no change is required in the underlying language modeling network. Experiments have shown that our model outperformed several strong baseline models on different data sets. We achieved a new state-of-the-art performance of 17.4 perplexity on the Wikitext-103 dataset. Additionally, visualizing the outputs of the phrase induction module showed that our model is able to learn approximate phrase-level structural knowledge without any annotation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.01702](http://arxiv.org/abs/1906.01702)

##### PDF
[http://arxiv.org/pdf/1906.01702](http://arxiv.org/pdf/1906.01702)

