---
layout: post
title: "Cross-Lingual Approaches to Reference Resolution in Dialogue Systems"
date: 2018-11-27 18:52:58
categories: arXiv_CL
tags: arXiv_CL Embedding
author: Amr Sharaf, Arpit Gupta, Hancheng Ge, Chetan Naik, Lambert Mathias
mathjax: true
---

* content
{:toc}

##### Abstract
In the slot-filling paradigm, where a user can refer back to slots in the context during the conversation, the goal of the contextual understanding system is to resolve the referring expressions to the appropriate slots in the context. In this paper, we build on the context carryover system~\citep{Naik2018ContextualSC}, which provides a scalable multi-domain framework for resolving references. However, scaling this approach across languages is not a trivial task, due to the large demand on acquisition of annotated data in the target language. Our main focus is on cross-lingual methods for reference resolution as a way to alleviate the need for annotated data in the target language. In the cross-lingual setup, we assume there is access to annotated resources as well as a well trained model in the source language and little to no annotated data in the target language. In this paper, we explore three different approaches for cross-lingual transfer \textemdash~\ delexicalization as data augmentation, multilingual embeddings and machine translation. We compare these approaches both on a low resource setting as well as a large resource setting. Our experiments show that multilingual embeddings and delexicalization via data augmentation have a significant impact in the low resource setting, but the gains diminish as the amount of available data in the target language increases. Furthermore, when combined with machine translation we can get performance very close to actual live data in the target language, with only 25\% of the data projected into the target language.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.11161](http://arxiv.org/abs/1811.11161)

##### PDF
[http://arxiv.org/pdf/1811.11161](http://arxiv.org/pdf/1811.11161)

