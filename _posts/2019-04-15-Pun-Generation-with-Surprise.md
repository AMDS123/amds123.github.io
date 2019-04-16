---
layout: post
title: "Pun Generation with Surprise"
date: 2019-04-15 03:40:16
categories: arXiv_CL
tags: arXiv_CL Text_Generation Language_Model
author: He He, Nanyun Peng, Percy Liang
mathjax: true
---

* content
{:toc}

##### Abstract
We tackle the problem of generating a pun sentence given a pair of homophones (e.g., "died" and "dyed"). Supervised text generation is inappropriate due to the lack of a large corpus of puns, and even if such a corpus existed, mimicry is at odds with generating novel content. In this paper, we propose an unsupervised approach to pun generation using a corpus of unhumorous text and what we call the local-global surprisal principle: we posit that in a pun sentence, there is a strong association between the pun word (e.g., "dyed") and the distant context, as well as a strong association between the alternative word (e.g., "died") and the immediate context. This contrast creates surprise and thus humor. We instantiate this principle for pun generation in two ways: (i) as a measure based on the ratio of probabilities under a language model, and (ii) a retrieve-and-edit approach based on words suggested by a skip-gram model. Human evaluation shows that our retrieve-and-edit approach generates puns successfully 31% of the time, tripling the success rate of a neural generation baseline.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.06828](http://arxiv.org/abs/1904.06828)

##### PDF
[http://arxiv.org/pdf/1904.06828](http://arxiv.org/pdf/1904.06828)

