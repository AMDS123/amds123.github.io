---
layout: post
title: "MDE: Multi Distance Embeddings for Link Prediction in Knowledge Graphs"
date: 2019-05-25 23:48:00
categories: arXiv_AI
tags: arXiv_AI Knowledge_Graph Knowledge Embedding Prediction Relation
author: Afshin Sadeghi, Damien Graux, Jens Lehmann
mathjax: true
---

* content
{:toc}

##### Abstract
Over the past decade, knowledge graphs became popular for capturing structured domain knowledge. Relational learning models enable the prediction of missing links inside knowledge graphs. More specifically, latent distance approaches model the relationships among entities via a distance between latent representations. Translating embedding models (e.g., TransE) are among the most popular latent distance approaches which use one distance function to learn multiple relation patterns. However, they are not capable of capturing symmetric relations. They also force relations with reflexive patterns to become symmetric and transitive. In order to improve distance based embedding, we propose multi-distance embeddings (MDE). Our solution is based on the idea that by learning independent embedding vectors for each entity and relation one can aggregate contrasting distance functions. Benefiting from MDE, we also develop supplementary distances resolving the above-mentioned limitations of TransE. We further propose an extended loss function for distance based embeddings and show that MDE and TransE are fully expressive using this loss function. Furthermore, we obtain a bound on the size of their embeddings for full expressivity. Our empirical results show that MDE significantly improves the translating embeddings and outperforms several state-of-the-art embedding models on benchmark datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.10702](http://arxiv.org/abs/1905.10702)

##### PDF
[http://arxiv.org/pdf/1905.10702](http://arxiv.org/pdf/1905.10702)

