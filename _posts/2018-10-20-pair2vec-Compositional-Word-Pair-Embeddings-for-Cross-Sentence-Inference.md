---
layout: post
title: "pair2vec: Compositional Word-Pair Embeddings for Cross-Sentence Inference"
date: 2018-10-20 21:37:08
categories: arXiv_CL
tags: arXiv_CL Adversarial Knowledge QA Attention Embedding Inference Relation
author: Mandar Joshi, Eunsol Choi, Omer Levy, Daniel S. Weld, Luke Zettlemoyer
mathjax: true
---

* content
{:toc}

##### Abstract
Reasoning about implied relationships (e.g. paraphrastic, common sense, encyclopedic) between pairs of words is crucial for many cross-sentence inference problems. This paper proposes new methods for learning and using embeddings of word pairs that implicitly represent background knowledge about such relationships. Our pairwise embeddings are computed as a compositional function of each word's representation, which is learned by maximizing the pointwise mutual information (PMI) with the contexts in which the the two words co-occur. We add these representations to the cross-sentence attention layer of existing inference models (e.g. BiDAF for QA, ESIM for NLI), instead of extending or replacing existing word embeddings. Experiments show a gain of 2.72% on the recently released SQuAD 2.0 and 1.3% on MultiNLI. Our representations also aid in better generalization with gains of around 6-7% on adversarial SQuAD datasets, and 8.8% on the adversarial entailment test set by Glockner et al.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.08854](http://arxiv.org/abs/1810.08854)

##### PDF
[http://arxiv.org/pdf/1810.08854](http://arxiv.org/pdf/1810.08854)

