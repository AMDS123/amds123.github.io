---
layout: post
title: "It's All in the Name: Mitigating Gender Bias with Name-Based Counterfactual Data Substitution"
date: 2019-09-02 21:33:03
categories: arXiv_CL
tags: arXiv_CL Embedding
author: Rowan Hall Maudslay, Hila Gonen, Ryan Cotterell, Simone Teufel
mathjax: true
---

* content
{:toc}

##### Abstract
This paper treats gender bias latent in word embeddings. Previous mitigation attempts rely on the operationalisation of gender bias as a projection over a linear subspace. An alternative approach is Counterfactual Data Augmentation (CDA), in which a corpus is duplicated and augmented to remove bias, e.g. by swapping all inherently-gendered words in the copy. We perform an empirical comparison of these approaches on the English Gigaword and Wikipedia, and find that whilst both successfully reduce direct bias and perform well in tasks which quantify embedding quality, CDA variants outperform projection-based methods at the task of drawing non-biased gender analogies by an average of 19% across both corpora. We propose two improvements to CDA: Counterfactual Data Substitution (CDS), a variant of CDA in which potentially biased text is randomly substituted to avoid duplication, and the Names Intervention, a novel name-pairing technique that vastly increases the number of words being treated. CDA/S with the Names Intervention is the only approach which is able to mitigate indirect gender bias: following debiasing, previously biased words are significantly less clustered according to gender (cluster purity is reduced by 49%), thus improving on the state-of-the-art for bias mitigation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.00871](http://arxiv.org/abs/1909.00871)

##### PDF
[http://arxiv.org/pdf/1909.00871](http://arxiv.org/pdf/1909.00871)

