---
layout: post
title: "Real-Time Open-Domain Question Answering with Dense-Sparse Phrase Index"
date: 2019-06-13 16:49:35
categories: arXiv_CL
tags: arXiv_CL Sparse QA Optimization Inference
author: Minjoon Seo, Jinhyuk Lee, Tom Kwiatkowski, Ankur P. Parikh, Ali Farhadi, Hannaneh Hajishirzi
mathjax: true
---

* content
{:toc}

##### Abstract
Existing open-domain question answering (QA) models are not suitable for real-time usage because they need to process several long documents on-demand for every input query. In this paper, we introduce the query-agnostic indexable representation of document phrases that can drastically speed up open-domain QA and also allows us to reach long-tail targets. In particular, our dense-sparse phrase encoding effectively captures syntactic, semantic, and lexical information of the phrases and eliminates the pipeline filtering of context documents. Leveraging optimization strategies, our model can be trained in a single 4-GPU server and serve entire Wikipedia (up to 60 billion phrases) under 2TB with CPUs only. Our experiments on SQuAD-Open show that our model is more accurate than previous models while achieving 6000x reduced computational cost, which translates into at least 58x faster end-to-end inference benchmark on CPUs.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1906.05807](https://arxiv.org/abs/1906.05807)

##### PDF
[https://arxiv.org/pdf/1906.05807](https://arxiv.org/pdf/1906.05807)

