---
layout: post
title: "Data Selection with Cluster-Based Language Difference Models and Cynical Selection"
date: 2019-04-09 20:39:07
categories: arXiv_CL
tags: arXiv_CL
author: Luc&#xed;a Santamar&#xed;a, Amittai Axelrod
mathjax: true
---

* content
{:toc}

##### Abstract
We present and apply two methods for addressing the problem of selecting relevant training data out of a general pool for use in tasks such as machine translation. Building on existing work on class-based language difference models, we first introduce a cluster-based method that uses Brown clusters to condense the vocabulary of the corpora. Secondly, we implement the cynical data selection method, which incrementally constructs a training corpus to efficiently model the task corpus. Both the cluster-based and the cynical data selection approaches are used for the first time within a machine translation system, and we perform a head-to-head comparison. Our intrinsic evaluations show that both new methods outperform the standard Moore-Lewis approach (cross-entropy difference), in terms of better perplexity and OOV rates on in-domain data. The cynical approach converges much quicker, covering nearly all of the in-domain vocabulary with 84% less data than the other methods. Furthermore, the new approaches can be used to select machine translation training data for training better systems. Our results confirm that class-based selection using Brown clusters is a viable alternative to POS-based class-based methods, and removes the reliance on a part-of-speech tagger. Additionally, we are able to validate the recently proposed cynical data selection method, showing that its performance in SMT models surpasses that of traditional cross-entropy difference methods and more closely matches the sentence length of the task corpus.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.04900](http://arxiv.org/abs/1904.04900)

##### PDF
[http://arxiv.org/pdf/1904.04900](http://arxiv.org/pdf/1904.04900)

