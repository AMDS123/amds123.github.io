---
layout: post
title: "Learning with fuzzy hypergraphs: a topical approach to query-oriented text summarization"
date: 2019-06-22 13:28:32
categories: arXiv_AI
tags: arXiv_AI Summarization Optimization Relation
author: Hadrien Van Lierde, Tommy W. S. Chow
mathjax: true
---

* content
{:toc}

##### Abstract
Existing graph-based methods for extractive document summarization represent sentences of a corpus as the nodes of a graph or a hypergraph in which edges depict relationships of lexical similarity between sentences. Such approaches fail to capture semantic similarities between sentences when they express a similar information but have few words in common and are thus lexically dissimilar. To overcome this issue, we propose to extract semantic similarities based on topical representations of sentences. Inspired by the Hierarchical Dirichlet Process, we propose a probabilistic topic model in order to infer topic distributions of sentences. As each topic defines a semantic connection among a group of sentences with a certain degree of membership for each sentence, we propose a fuzzy hypergraph model in which nodes are sentences and fuzzy hyperedges are topics. To produce an informative summary, we extract a set of sentences from the corpus by simultaneously maximizing their relevance to a user-defined query, their centrality in the fuzzy hypergraph and their coverage of topics present in the corpus. We formulate a polynomial time algorithm building on the theory of submodular functions to solve the associated optimization problem. A thorough comparative analysis with other graph-based summarization systems is included in the paper. Our obtained results show the superiority of our method in terms of content coverage of the summaries.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.09445](http://arxiv.org/abs/1906.09445)

##### PDF
[http://arxiv.org/pdf/1906.09445](http://arxiv.org/pdf/1906.09445)

