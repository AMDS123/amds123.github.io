---
layout: post
title: "Alternative Weighting Schemes for ELMo Embeddings"
date: 2019-04-05 09:24:36
categories: arXiv_CL
tags: arXiv_CL Embedding Language_Model
author: Nils Reimers, Iryna Gurevych
mathjax: true
---

* content
{:toc}

##### Abstract
ELMo embeddings (Peters et. al, 2018) had a huge impact on the NLP community and may recent publications use these embeddings to boost the performance for downstream NLP tasks. However, integration of ELMo embeddings in existent NLP architectures is not straightforward. In contrast to traditional word embeddings, like GloVe or word2vec embeddings, the bi-directional language model of ELMo produces three 1024 dimensional vectors per token in a sentence. Peters et al. proposed to learn a task-specific weighting of these three vectors for downstream tasks. However, this proposed weighting scheme is not feasible for certain tasks, and, as we will show, it does not necessarily yield optimal performance. We evaluate different methods that combine the three vectors from the language model in order to achieve the best possible performance in downstream NLP tasks. We notice that the third layer of the published language model often decreases the performance. By learning a weighted average of only the first two layers, we are able to improve the performance for many datasets. Due to the reduced complexity of the language model, we have a training speed-up of 19-44% for the downstream task.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1904.02954](https://arxiv.org/abs/1904.02954)

##### PDF
[https://arxiv.org/pdf/1904.02954](https://arxiv.org/pdf/1904.02954)

