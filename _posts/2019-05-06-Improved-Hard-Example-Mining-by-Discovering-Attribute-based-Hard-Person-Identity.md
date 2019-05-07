---
layout: post
title: "Improved Hard Example Mining by Discovering Attribute-based Hard Person Identity"
date: 2019-05-06 15:38:36
categories: arXiv_CV
tags: arXiv_CV Re-identification GAN Person_Re-identification
author: Xiao Wang, Ziliang Chen, Rui Yang, Bin Luo, Jin Tang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose Hard Person Identity Mining (HPIM) that attempts to refine the hard example mining to improve the exploration efficacy in person re-identification. It is motivated by following observation: the more attributes some people share, the more difficult to separate their identities. Based on this observation, we develop HPIM via a transferred attribute describer, a deep multi-attribute classifier trained from the source noisy person attribute datasets. We encode each image into the attribute probabilistic description in the target person re-ID dataset. Afterwards in the attribute code space, we consider each person as a distribution to generate his view-specific attribute codes in different practical scenarios. Hence we estimate the person-specific statistical moments from zeroth to higher order, which are further used to calculate the central moment discrepancies between persons. Such discrepancy is a ground to choose hard identity to organize proper mini-batches, without concerning the person representation changing in metric learning. It presents as a complementary tool of hard example mining, which helps to explore the global instead of the local hard example constraint in the mini-batch built by randomly sampled identities. Extensive experiments on two person re-identification benchmarks validated the effectiveness of our proposed algorithm.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.02102](http://arxiv.org/abs/1905.02102)

##### PDF
[http://arxiv.org/pdf/1905.02102](http://arxiv.org/pdf/1905.02102)

