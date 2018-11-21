---
layout: post
title: "Almost Zero-Resource ASR-free Keyword Spotting using Multilingual Bottleneck Features and Correspondence Autoencoders"
date: 2018-11-14 09:29:11
categories: arXiv_SD
tags: arXiv_SD Sparse
author: Raghav Menon, Herman Kamper, John Quinn, Thomas Niesler
mathjax: true
---

* content
{:toc}

##### Abstract
We compare features for dynamic time warping based keyword spotting in an almost zero-resource setting. The objective is to support United Nations (UN) humanitarian relief efforts in parts of Africa with severely under-resourced languages. As supervised resource, we restrict ourselves to an easily-compiled small set of isolated keywords. For feature extraction, we integrate a multilingual bottleneck feature extractor (BNF), trained on well-resourced out-of-domain languages, with a correspondence autoencoder (CAE), trained on extremely sparse in-domain data. We find that, on their own, BNFs and CAE features achieve more than 2% absolute performance improvement over baseline MFCCs. However, by using BNFs as input to the CAE, even better performance is achieved, with an 11% absolute improvement in ROC AUC over MFCCs and twice as many top-10 retrievals. We conclude that integrating BNFs with the CAE allows both large out-of-domain and sparse in-domain resources to be exploited for improved ASR-free keyword spotting.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.08284](http://arxiv.org/abs/1811.08284)

##### PDF
[http://arxiv.org/pdf/1811.08284](http://arxiv.org/pdf/1811.08284)

