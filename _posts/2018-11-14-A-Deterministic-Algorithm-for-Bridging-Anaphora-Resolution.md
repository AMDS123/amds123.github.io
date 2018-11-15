---
layout: post
title: "A Deterministic Algorithm for Bridging Anaphora Resolution"
date: 2018-11-14 10:49:39
categories: arXiv_CL
tags: arXiv_CL Knowledge Embedding
author: Yufang Hou
mathjax: true
---

* content
{:toc}

##### Abstract
Previous work on bridging anaphora resolution (Poesio et al., 2004; Hou et al., 2013b) use syntactic preposition patterns to calculate word relatedness. However, such patterns only consider NPs' head nouns and hence do not fully capture the semantics of NPs. Recently, Hou (2018) created word embeddings (embeddings_PP) to capture associative similarity (ie, relatedness) between nouns by exploring the syntactic structure of noun phrases. But embeddings_PP only contains word representations for nouns. In this paper, we create new word vectors by combining embeddings_PP with GloVe. This new word embeddings (embeddings_bridging) are a more general lexical knowledge resource for bridging and allow us to represent the meaning of an NP beyond its head easily. We therefore develop a deterministic approach for bridging anaphora resolution, which represents the semantics of an NP based on its head noun and modifications. We show that this simple approach achieves the competitive results compared to the best system in Hou et al.(2013b) which explores Markov Logic Networks to model the problem. Additionally, we further improve the results for bridging anaphora resolution reported in Hou (2018) by combining our simple deterministic approach with Hou et al.(2013b)'s best system MLN II.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.05721](http://arxiv.org/abs/1811.05721)

##### PDF
[http://arxiv.org/pdf/1811.05721](http://arxiv.org/pdf/1811.05721)

