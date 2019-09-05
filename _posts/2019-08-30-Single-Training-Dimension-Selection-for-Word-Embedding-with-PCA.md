---
layout: post
title: "Single Training Dimension Selection for Word Embedding with PCA"
date: 2019-08-30 23:19:41
categories: arXiv_CL
tags: arXiv_CL Sentiment Embedding
author: Yu Wang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a fast and reliable method based on PCA to select the number of dimensions for word embeddings. First, we train one embedding with a generous upper bound (e.g. 1,000) of dimensions. Then we transform the embeddings using PCA and incrementally remove the lesser dimensions one at a time while recording the embeddings' performance on language tasks. Lastly, we select the number of dimensions while balancing model size and accuracy. Experiments using various datasets and language tasks demonstrate that we are able to train 10 times fewer sets of embeddings while retaining optimal performance. Researchers interested in training the best-performing embeddings for downstream tasks, such as sentiment analysis, question answering and hypernym extraction, as well as those interested in embedding compression should find the method helpful.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.01761](http://arxiv.org/abs/1909.01761)

##### PDF
[http://arxiv.org/pdf/1909.01761](http://arxiv.org/pdf/1909.01761)

