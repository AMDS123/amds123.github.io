---
layout: post
title: "Predicting Target Language CCG Supertags Improves Neural Machine Translation"
date: 2017-07-18 12:07:45
categories: arXiv_CL
tags: arXiv_CL Embedding NMT
author: Maria Nadejde, Siva Reddy, Rico Sennrich, Tomasz Dwojak, Marcin Junczys-Dowmunt, Philipp Koehn, Alexandra Birch
mathjax: true
---

* content
{:toc}

##### Abstract
Neural machine translation (NMT) models are able to partially learn syntactic information from sequential lexical information. Still, some complex syntactic phenomena such as prepositional phrase attachment are poorly modeled. This work aims to answer two questions: 1) Does explicitly modeling target language syntax help NMT? 2) Is tight integration of words and syntax better than multitask training? We introduce syntactic information in the form of CCG supertags in the decoder, by interleaving the target supertags with the word sequence. Our results on WMT data show that explicitly modeling target-syntax improves machine translation quality for German->English, a high-resource pair, and for Romanian->English, a low-resource pair and also several syntactic phenomena including prepositional phrase attachment. Furthermore, a tight coupling of words and syntax improves translation quality more than multitask training. By combining target-syntax with adding source-side dependency labels in the embedding layer, we obtain a total improvement of 0.9 BLEU for German->English and 1.2 BLEU for Romanian->English.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1702.01147](https://arxiv.org/abs/1702.01147)

##### PDF
[https://arxiv.org/pdf/1702.01147](https://arxiv.org/pdf/1702.01147)

