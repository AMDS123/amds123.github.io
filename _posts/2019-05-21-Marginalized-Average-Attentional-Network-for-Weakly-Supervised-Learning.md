---
layout: post
title: "Marginalized Average Attentional Network for Weakly-Supervised Learning"
date: 2019-05-21 12:49:22
categories: arXiv_CV
tags: arXiv_CV Salient Attention
author: Yuan Yuan, Yueming Lyu, Xi Shen, Ivor W. Tsang, Dit-Yan Yeung
mathjax: true
---

* content
{:toc}

##### Abstract
In weakly-supervised temporal action localization, previous works have failed to locate dense and integral regions for each entire action due to the overestimation of the most salient regions. To alleviate this issue, we propose a marginalized average attentional network (MAAN) to suppress the dominant response of the most salient regions in a principled manner. The MAAN employs a novel marginalized average aggregation (MAA) module and learns a set of latent discriminative probabilities in an end-to-end fashion. MAA samples multiple subsets from the video snippet features according to a set of latent discriminative probabilities and takes the expectation over all the averaged subset features. Theoretically, we prove that the MAA module with learned latent discriminative probabilities successfully reduces the difference in responses between the most salient regions and the others. Therefore, MAAN is able to generate better class activation sequences and identify dense and integral action regions in the videos. Moreover, we propose a fast algorithm to reduce the complexity of constructing MAA from O($2^T$) to O($T^2$). Extensive experiments on two large-scale video datasets show that our MAAN achieves superior performance on weakly-supervised temporal action localization

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.08586](http://arxiv.org/abs/1905.08586)

##### PDF
[http://arxiv.org/pdf/1905.08586](http://arxiv.org/pdf/1905.08586)

