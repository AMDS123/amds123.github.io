---
layout: post
title: "Characterizing the impact of geometric properties of word embeddings on task performance"
date: 2019-04-09 18:53:00
categories: arXiv_CL
tags: arXiv_CL Embedding Language_Model
author: Brendan Whitaker, Denis Newman-Griffis, Aparajita Haldar, Hakan Ferhatosmanoglu, Eric Fosler-Lussier
mathjax: true
---

* content
{:toc}

##### Abstract
Analysis of word embedding properties to inform their use in downstream NLP tasks has largely been studied by assessing nearest neighbors. However, geometric properties of the continuous feature space contribute directly to the use of embedding features in downstream models, and are largely unexplored. We consider four properties of word embedding geometry, namely: position relative to the origin, distribution of features in the vector space, global pairwise distances, and local pairwise distances. We define a sequence of transformations to generate new embeddings that expose subsets of these properties to downstream models and evaluate change in task performance to understand the contribution of each property to NLP models. We transform publicly available pretrained embeddings from three popular toolkits (word2vec, GloVe, and FastText) and evaluate on a variety of intrinsic tasks, which model linguistic information in the vector space, and extrinsic tasks, which use vectors as input to machine learning models. We find that intrinsic evaluations are highly sensitive to absolute position, while extrinsic tasks rely primarily on local similarity. Our findings suggest that future embedding models and post-processing techniques should focus primarily on similarity to nearby points in vector space.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.04866](http://arxiv.org/abs/1904.04866)

##### PDF
[http://arxiv.org/pdf/1904.04866](http://arxiv.org/pdf/1904.04866)

