---
layout: post
title: "Multilingual Extractive Reading Comprehension by Runtime Machine Translation"
date: 2018-11-02 21:41:06
categories: arXiv_CL
tags: arXiv_CL Attention NMT
author: Akari Asai, Akiko Eriguchi, Kazuma Hashimoto, Yoshimasa Tsuruoka
mathjax: true
---

* content
{:toc}

##### Abstract
Despite recent work in Reading Comprehension (RC), progress has been mostly limited to English due to the lack of large-scale datasets in other languages. In this work, we introduce the first RC system for languages without RC training data. Given a target language without RC training data and a pivot language with RC training data (e.g. English), our method leverages existing RC resources in the pivot language by combining a competitive RC model in the pivot language with an attentive Neural Machine Translation (NMT) model. We first translate the data from the target to the pivot language, and then obtain an answer using the RC model in the pivot language. Finally, we recover the corresponding answer in the original language using soft-alignment attention scores from the NMT model. We create evaluation sets of RC data in two non-English languages, namely Japanese and French, to evaluate our method. Experimental results on these datasets show that our method significantly outperforms a back-translation baseline of a state-of-the-art product-level machine translation system.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1809.03275](https://arxiv.org/abs/1809.03275)

##### PDF
[https://arxiv.org/pdf/1809.03275](https://arxiv.org/pdf/1809.03275)

