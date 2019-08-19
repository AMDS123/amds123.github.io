---
layout: post
title: "Incorporating Word and Subword Units in Unsupervised Machine Translation Using Language Model Rescoring"
date: 2019-08-16 10:44:25
categories: arXiv_CL
tags: arXiv_CL Embedding NMT Language_Model
author: Zihan Liu, Yan Xu, Genta Indra Winata, Pascale Fung
mathjax: true
---

* content
{:toc}

##### Abstract
This paper describes CAiRE's submission to the unsupervised machine translation track of the WMT'19 news shared task from German to Czech. We leverage a phrase-based statistical machine translation (PBSMT) model and a pre-trained language model to combine word-level neural machine translation (NMT) and subword-level NMT models without using any parallel data. We propose to solve the morphological richness problem of languages by training byte-pair encoding (BPE) embeddings for German and Czech separately, and they are aligned using MUSE (Conneau et al., 2018). To ensure the fluency and consistency of translations, a rescoring mechanism is proposed that reuses the pre-trained language model to select the translation candidates generated through beam search. Moreover, a series of pre-processing and post-processing approaches are applied to improve the quality of final translations.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.05925](https://arxiv.org/abs/1908.05925)

##### PDF
[https://arxiv.org/pdf/1908.05925](https://arxiv.org/pdf/1908.05925)

