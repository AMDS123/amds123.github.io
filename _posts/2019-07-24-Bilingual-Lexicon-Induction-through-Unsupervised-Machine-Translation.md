---
layout: post
title: "Bilingual Lexicon Induction through Unsupervised Machine Translation"
date: 2019-07-24 22:30:04
categories: arXiv_AI
tags: arXiv_AI Embedding Language_Model
author: Mikel Artetxe, Gorka Labaka, Eneko Agirre
mathjax: true
---

* content
{:toc}

##### Abstract
A recent research line has obtained strong results on bilingual lexicon induction by aligning independently trained word embeddings in two languages and using the resulting cross-lingual embeddings to induce word translation pairs through nearest neighbor or related retrieval methods. In this paper, we propose an alternative approach to this problem that builds on the recent work on unsupervised machine translation. This way, instead of directly inducing a bilingual lexicon from cross-lingual embeddings, we use them to build a phrase-table, combine it with a language model, and use the resulting machine translation system to generate a synthetic parallel corpus, from which we extract the bilingual lexicon using statistical word alignment techniques. As such, our method can work with any word embedding and cross-lingual mapping technique, and it does not require any additional resource besides the monolingual corpus used to train the embeddings. When evaluated on the exact same cross-lingual embeddings, our proposed method obtains an average improvement of 6 accuracy points over nearest neighbor and 4 points over CSLS retrieval, establishing a new state-of-the-art in the standard MUSE dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.10761](http://arxiv.org/abs/1907.10761)

##### PDF
[http://arxiv.org/pdf/1907.10761](http://arxiv.org/pdf/1907.10761)

