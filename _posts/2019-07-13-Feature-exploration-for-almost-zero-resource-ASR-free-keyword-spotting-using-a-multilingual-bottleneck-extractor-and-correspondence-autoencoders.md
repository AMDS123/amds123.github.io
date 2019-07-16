---
layout: post
title: "Feature exploration for almost zero-resource ASR-free keyword spotting using a multilingual bottleneck extractor and correspondence autoencoders"
date: 2019-07-13 01:58:31
categories: arXiv_SD
tags: arXiv_SD Sparse GAN
author: Raghav Menon, Herman Kamper, Ewald van der Westhuizen, John Quinn, Thomas Niesler
mathjax: true
---

* content
{:toc}

##### Abstract
We compare features for dynamic time warping (DTW) when used to bootstrap keyword spotting (KWS) in an almost zero-resource setting. Such quickly-deployable systems aim to support United Nations (UN) humanitarian relief efforts in parts of Africa with severely under-resourced languages. Our objective is to identify acoustic features that provide acceptable KWS performance in such environments. As supervised resource, we restrict ourselves to a small, easily acquired and independently compiled set of isolated keywords. For feature extraction, a multilingual bottleneck feature (BNF) extractor, trained on well-resourced out-of-domain languages, is integrated with a correspondence autoencoder (CAE) trained on extremely sparse in-domain data. On their own, BNFs and CAE features are shown to achieve a more than 2% absolute performance improvement over baseline MFCCs. However, by using BNFs as input to the CAE, even better performance is achieved, with a more than 11% absolute improvement in ROC AUC over MFCCs and more than twice as many top-10 retrievals for two evaluated languages, English and Luganda. We conclude that integrating BNFs with the CAE allows both large out-of-domain and sparse in-domain resources to be exploited for improved ASR-free keyword spotting.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.08284](http://arxiv.org/abs/1811.08284)

##### PDF
[http://arxiv.org/pdf/1811.08284](http://arxiv.org/pdf/1811.08284)

