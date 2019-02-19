---
layout: post
title: "On resampling vs. adjusting probabilistic graphical models in estimation of distribution algorithms"
date: 2019-02-15 20:59:20
categories: arXiv_AI
tags: arXiv_AI Sparse Relation
author: Mohamed El Yafrani, Marcella S. R. Martins, Myriam R. B. S. Delgado, Inkyung Sung, Ricardo L&#xfc;ders, Markus Wagner
mathjax: true
---

* content
{:toc}

##### Abstract
The Bayesian Optimisation Algorithm (BOA) is an Estimation of Distribution Algorithm (EDA) that uses a Bayesian network as probabilistic graphical model (PGM). Determining the optimal Bayesian network structure given a solution sample is an NP-hard problem. This step should be completed at each iteration of BOA, resulting in a very time-consuming process. For this reason most implementations use greedy estimation algorithms such as K2. However, we show in this paper that significant changes in PGM structure do not occur so frequently, and can be particularly sparse at the end of evolution. A statistical study of BOA is thus presented to characterise a pattern of PGM adjustments that can be used as a guide to reduce the frequency of PGM updates during the evolutionary process. This is accomplished by proposing a new BOA-based optimisation approach (FBOA) whose PGM is not updated at each iteration. This new approach avoids the computational burden usually found in the standard BOA. The results compare the performances of both algorithms on an NK-landscape optimisation problem using the correlation between the ruggedness and the expected runtime over enumerated instances. The experiments show that FBOA presents competitive results while significantly saving computational time.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.05946](http://arxiv.org/abs/1902.05946)

##### PDF
[http://arxiv.org/pdf/1902.05946](http://arxiv.org/pdf/1902.05946)

