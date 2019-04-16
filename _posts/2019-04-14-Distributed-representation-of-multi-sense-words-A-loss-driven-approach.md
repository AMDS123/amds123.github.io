---
layout: post
title: "Distributed representation of multi-sense words: A loss-driven approach"
date: 2019-04-14 17:01:26
categories: arXiv_AI
tags: arXiv_AI Language_Model
author: Saurav Manchanda, George Karypis
mathjax: true
---

* content
{:toc}

##### Abstract
Word2Vec's Skip Gram model is the current state-of-the-art approach for estimating the distributed representation of words. However, it assumes a single vector per word, which is not well-suited for representing words that have multiple senses. This work presents LDMI, a new model for estimating distributional representations of words. LDMI relies on the idea that, if a word carries multiple senses, then having a different representation for each of its senses should lead to a lower loss associated with predicting its co-occurring words, as opposed to the case when a single vector representation is used for all the senses. After identifying the multi-sense words, LDMI clusters the occurrences of these words to assign a sense to each occurrence. Experiments on the contextual word similarity task show that LDMI leads to better performance than competing approaches.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.06725](http://arxiv.org/abs/1904.06725)

##### PDF
[http://arxiv.org/pdf/1904.06725](http://arxiv.org/pdf/1904.06725)

