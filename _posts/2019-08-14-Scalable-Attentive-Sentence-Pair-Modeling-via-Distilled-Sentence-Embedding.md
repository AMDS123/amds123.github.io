---
layout: post
title: "Scalable Attentive Sentence-Pair Modeling via Distilled Sentence Embedding"
date: 2019-08-14 15:06:48
categories: arXiv_CL
tags: arXiv_CL Knowledge Attention Embedding
author: Oren Barkan, Noam Razin, Itzik Malkiel, Ori Katz, Avi Caciularu, Noam Koenigstein
mathjax: true
---

* content
{:toc}

##### Abstract
Attention based models have become the new state-of-the-art in natural language understanding tasks such as question-answering and sentence similarity. Recent models, such as BERT and XLNet, score a pair of sentences (A and B) using multiple cross-attention operations - a process in which each word in sentence A attends to all words in sentence B and vice versa. As a result, computing the similarity between a query sentence and a set of candidate sentences, requires the propagation of all query-candidate sentence-pairs throughout a stack of cross-attention layers. This exhaustive process becomes computationally prohibitive when the number of candidate sentences is large. In contrast, sentence embedding techniques learn a sentence-to-vector mapping and compute the similarity between the sentence vectors via simple elementary operations such as dot product or cosine similarity. In this paper, we introduce a sentence embedding method that is based on knowledge distillation from cross-attentive models, focusing on sentence-pair tasks. The outline of the proposed method is as follows: Given a cross-attentive teacher model (e.g. a fine-tuned BERT), we train a sentence embedding based student model to reconstruct the sentence-pair scores obtained by the teacher model. We empirically demonstrate the effectiveness of our distillation method on five GLUE sentence-pair tasks. Our method significantly outperforms several ELMO variants and other sentence embedding methods, while accelerating computation of the query-candidate sentence-pairs similarities by several orders of magnitude, with an average relative degradation of 4.6% compared to BERT.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.05161](http://arxiv.org/abs/1908.05161)

##### PDF
[http://arxiv.org/pdf/1908.05161](http://arxiv.org/pdf/1908.05161)

