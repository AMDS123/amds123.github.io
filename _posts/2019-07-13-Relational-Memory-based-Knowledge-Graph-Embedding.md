---
layout: post
title: "Relational Memory-based Knowledge Graph Embedding"
date: 2019-07-13 14:01:27
categories: arXiv_CL
tags: arXiv_CL Knowledge_Graph Knowledge Attention Embedding Classification Relation
author: Dai Quoc Nguyen, Tu Dinh Nguyen, Dinh Phung
mathjax: true
---

* content
{:toc}

##### Abstract
Knowledge graph embedding models often suffer from a limitation of remembering existing triples to predict new triples. To overcome this issue, we introduce a novel embedding model, named R-MeN, that explores a relational memory network to model relationship triples. In R-MeN, we simply represent each triple as a sequence of 3 input vectors which recurrently interact with a relational memory. This memory network is constructed to incorporate new information using a self-attention mechanism over the memory and input vectors to return a corresponding output vector for every timestep. Consequently, we obtain 3 output vectors which are then multiplied element-wisely into a single one; and finally, we feed this vector to a linear neural layer to produce a scalar score for the triple. Experimental results show that our proposed R-MeN obtains state-of-the-art results on two well-known benchmark datasets WN11 and FB13 for triple classification task.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.06080](http://arxiv.org/abs/1907.06080)

##### PDF
[http://arxiv.org/pdf/1907.06080](http://arxiv.org/pdf/1907.06080)

