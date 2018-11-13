---
layout: post
title: "End-to-end Structure-Aware Convolutional Networks for Knowledge Base Completion"
date: 2018-11-11 18:07:44
categories: arXiv_AI
tags: arXiv_AI Knowledge_Graph Knowledge Embedding CNN Relation
author: Chao Shang, Yun Tang, Jing Huang, Jinbo Bi, Xiaodong He, Bowen Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
Knowledge graph embedding has been an active research topic for knowledge base completion, with progressive improvement from the initial TransE, TransH, DistMult et al to the current state-of-the-art ConvE. ConvE uses 2D convolution over embeddings and multiple layers of nonlinear features to model knowledge graphs. The model can be efficiently trained and scalable to large knowledge graphs. However, there is no structure enforcement in the embedding space of ConvE. The recent graph convolutional network (GCN) provides another way of learning graph node embedding by successfully utilizing graph connectivity structure. In this work, we propose a novel end-to-end Structure-Aware Convolutional Networks (SACN) that take the benefit of GCN and ConvE together. SACN consists of an encoder of a weighted graph convolutional network (WGCN), and a decoder of a convolutional network called Conv-TransE. WGCN utilizes knowledge graph node structure, node attributes and relation types. It has learnable weights that collect adaptive amount of information from neighboring graph nodes, resulting in more accurate embeddings of graph nodes. In addition, the node attributes are added as the nodes and are easily integrated into the WGCN. The decoder Conv-TransE extends the state-of-the-art ConvE to be translational between entities and relations while keeps the state-of-the-art performance as ConvE. We demonstrate the effectiveness of our proposed SACN model on standard FB15k-237 and WN18RR datasets, and present about 10% relative improvement over the state-of-the-art ConvE in terms of HITS@1, HITS@3 and HITS@10.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.04441](http://arxiv.org/abs/1811.04441)

##### PDF
[http://arxiv.org/pdf/1811.04441](http://arxiv.org/pdf/1811.04441)

