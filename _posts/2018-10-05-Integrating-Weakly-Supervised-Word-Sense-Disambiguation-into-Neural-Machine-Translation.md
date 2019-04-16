---
layout: post
title: "Integrating Weakly Supervised Word Sense Disambiguation into Neural Machine Translation"
date: 2018-10-05 11:20:39
categories: arXiv_CL
tags: arXiv_CL Weakly_Supervised NMT
author: Xiao Pu, Nikolaos Pappas, James Henderson, Andrei Popescu-Belis
mathjax: true
---

* content
{:toc}

##### Abstract
This paper demonstrates that word sense disambiguation (WSD) can improve neural machine translation (NMT) by widening the source context considered when modeling the senses of potentially ambiguous words. We first introduce three adaptive clustering algorithms for WSD, based on k-means, Chinese restaurant processes, and random walks, which are then applied to large word contexts represented in a low-rank space and evaluated on SemEval shared-task data. We then learn word vectors jointly with sense vectors defined by our best WSD method, within a state-of-the-art NMT system. We show that the concatenation of these vectors, and the use of a sense selection mechanism based on the weighted average of sense vectors, outperforms several baselines including sense-aware ones. This is demonstrated by translation on five language pairs. The improvements are above one BLEU point over strong NMT baselines, +4% accuracy over all ambiguous nouns and verbs, or +20% when scored manually over several challenging words.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.02614](https://arxiv.org/abs/1810.02614)

##### PDF
[https://arxiv.org/pdf/1810.02614](https://arxiv.org/pdf/1810.02614)

