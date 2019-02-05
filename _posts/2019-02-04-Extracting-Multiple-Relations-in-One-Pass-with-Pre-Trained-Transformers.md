---
layout: post
title: "Extracting Multiple-Relations in One-Pass with Pre-Trained Transformers"
date: 2019-02-04 04:42:08
categories: arXiv_AI
tags: arXiv_AI Relation_Extraction Attention Embedding Prediction Relation
author: Haoyu Wang, Ming Tan, Mo Yu, Shiyu Chang, Dakuo Wang, Kun Xu, Xiaoxiao Guo, Saloni Potdar
mathjax: true
---

* content
{:toc}

##### Abstract
Most approaches to extraction multiple relations from a paragraph require multiple passes over the paragraph. In practice, multiple passes are computationally expensive and this makes difficult to scale to longer paragraphs and larger text corpora. In this work, we focus on the task of multiple relation extraction by encoding the paragraph only once (one-pass). We build our solution on the pre-trained self-attentive (Transformer) models, where we first add a structured prediction layer to handle extraction between multiple entity pairs, then enhance the paragraph embedding to capture multiple relational information associated with each entity with an entity-aware attention technique. We show that our approach is not only scalable but can also perform state-of-the-art on the standard benchmark ACE 2005.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.01030](http://arxiv.org/abs/1902.01030)

##### PDF
[http://arxiv.org/pdf/1902.01030](http://arxiv.org/pdf/1902.01030)

