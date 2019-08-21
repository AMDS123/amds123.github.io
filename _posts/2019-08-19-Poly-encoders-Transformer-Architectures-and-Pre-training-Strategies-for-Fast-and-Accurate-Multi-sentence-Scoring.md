---
layout: post
title: "Poly-encoders: Transformer Architectures and Pre-training Strategies for Fast and Accurate Multi-sentence Scoring"
date: 2019-08-19 19:07:46
categories: arXiv_AI
tags: arXiv_AI Attention
author: Samuel Humeau, Kurt Shuster, Marie-Anne Lachaux, Jason Weston
mathjax: true
---

* content
{:toc}

##### Abstract
The use of deep pre-trained bidirectional transformers has led to remarkable progress in a number of applications (Devlin et al., 2018). For tasks that make pairwise comparisons between sequences, matching a given input with a corresponding label, two approaches are common: Cross-encoders performing full self-attention over the pair and Bi-encoders encoding the pair separately. The former often performs better, but is too slow for practical use. In this work, we develop a new transformer architecture, the Poly-encoder, that learns global rather than token level self-attention features. We perform a detailed comparison of all three approaches, including what pre-training and fine-tuning strategies work best. We show our models achieve state-of-the-art results on three existing tasks; that Poly-encoders are faster than Cross-encoders and more accurate than Bi-encoders; and that the best results are obtained by pre-training on large datasets similar to the downstream tasks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.01969](http://arxiv.org/abs/1905.01969)

##### PDF
[http://arxiv.org/pdf/1905.01969](http://arxiv.org/pdf/1905.01969)

