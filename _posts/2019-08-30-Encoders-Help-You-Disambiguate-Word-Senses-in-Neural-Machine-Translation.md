---
layout: post
title: "Encoders Help You Disambiguate Word Senses in Neural Machine Translation"
date: 2019-08-30 15:00:19
categories: arXiv_CL
tags: arXiv_CL Attention Embedding NMT
author: Gongbo Tang, Rico Sennrich, Joakim Nivre
mathjax: true
---

* content
{:toc}

##### Abstract
Neural machine translation (NMT) has achieved new state-of-the-art performance in translating ambiguous words. However, it is still unclear which component dominates the process of disambiguation. In this paper, we explore the ability of NMT encoders and decoders to disambiguate word senses by evaluating hidden states and investigating the distributions of self-attention. We train a classifier to predict whether a translation is correct given the representation of an ambiguous noun. We find that encoder hidden states outperform word embeddings significantly which indicates that encoders adequately encode relevant information for disambiguation into hidden states. In contrast to encoders, the effect of decoder is different in models with different architectures. Moreover, the attention weights and attention entropy show that self-attention can detect ambiguous nouns and distribute more attention to the context.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.11771](http://arxiv.org/abs/1908.11771)

##### PDF
[http://arxiv.org/pdf/1908.11771](http://arxiv.org/pdf/1908.11771)

