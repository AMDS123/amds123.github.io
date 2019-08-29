---
layout: post
title: "Unlearn Dataset Bias in Natural Language Inference by Fitting the Residual"
date: 2019-08-28 15:02:45
categories: arXiv_CL
tags: arXiv_CL Inference
author: He He, Sheng Zha, Haohan Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Statistical natural language inference (NLI) models are susceptible to learning dataset bias: superficial cues that happen to associate with the label on a particular dataset, but are not useful in general, e.g., negation words indicate contradiction. As exposed by several recent challenge datasets, these models perform poorly when such association is absent, e.g., predicting that "I love dogs" contradicts "I don't love cats". Our goal is to design learning algorithms that guard against known dataset bias. We formalize the concept of dataset bias under the framework of distribution shift and present a simple debiasing algorithm based on residual fitting, which we call DRiFt. We first learn a biased model that only uses features that are known to relate to dataset bias. Then, we train a debiased model that fits to the residual of the biased model, focusing on examples that cannot be predicted well by biased features only. We use DRiFt to train three high-performing NLI models on two benchmark datasets, SNLI and MNLI. Our debiased models achieve significant gains over baseline models on two challenge test sets, while maintaining reasonable performance on the original test sets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.10763](http://arxiv.org/abs/1908.10763)

##### PDF
[http://arxiv.org/pdf/1908.10763](http://arxiv.org/pdf/1908.10763)

