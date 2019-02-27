---
layout: post
title: "Improving a tf-idf weighted document vector embedding"
date: 2019-02-26 11:55:35
categories: arXiv_CL
tags: arXiv_CL Review QA Embedding Language_Model
author: Craig W. Schmidt
mathjax: true
---

* content
{:toc}

##### Abstract
We examine a number of methods to compute a dense vector embedding for a document in a corpus, given a set of word vectors such as those from word2vec or GloVe. We describe two methods that can improve upon a simple weighted sum, that are optimal in the sense that they maximizes a particular weighted cosine similarity measure. 
 We consider several weighting functions, including inverse document frequency (idf), smooth inverse frequency (SIF), and the sub-sampling function used in word2vec. We find that idf works best for our applications. We also use common component removal proposed by Arora et al. as a post-process and find it is helpful in most cases. 
 We compare these embeddings variations to the doc2vec embedding on a new evaluation task using TripAdvisor reviews, and also on the CQADupStack benchmark from the literature.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.09875](http://arxiv.org/abs/1902.09875)

##### PDF
[http://arxiv.org/pdf/1902.09875](http://arxiv.org/pdf/1902.09875)

