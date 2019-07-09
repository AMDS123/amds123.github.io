---
layout: post
title: "Best Practices for Learning Domain-Specific Cross-Lingual Embeddings"
date: 2019-07-06 10:45:45
categories: arXiv_CL
tags: arXiv_CL Knowledge Embedding Transfer_Learning
author: Lena Shakurova, Beata Nyari, Chao Li, Mihai Rotaru
mathjax: true
---

* content
{:toc}

##### Abstract
Cross-lingual embeddings aim to represent words in multiple languages in a shared vector space by capturing semantic similarities across languages. They are a crucial component for scaling tasks to multiple languages by transferring knowledge from languages with rich resources to low-resource languages. A common approach to learning cross-lingual embeddings is to train monolingual embeddings separately for each language and learn a linear projection from the monolingual spaces into a shared space, where the mapping relies on a small seed dictionary. While there are high-quality generic seed dictionaries and pre-trained cross-lingual embeddings available for many language pairs, there is little research on how they perform on specialised tasks. In this paper, we investigate the best practices for constructing the seed dictionary for a specific domain. We evaluate the embeddings on the sequence labelling task of Curriculum Vitae parsing and show that the size of a bilingual dictionary, the frequency of the dictionary words in the domain corpora and the source of data (task-specific vs generic) influence the performance. We also show that the less training data is available in the low-resource language, the more the construction of the bilingual dictionary matters, and demonstrate that some of the choices are crucial in the zero-shot transfer learning case.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.03112](http://arxiv.org/abs/1907.03112)

##### PDF
[http://arxiv.org/pdf/1907.03112](http://arxiv.org/pdf/1907.03112)

