---
layout: post
title: "Inoculation by Fine-Tuning: A Method for Analyzing Challenge Datasets"
date: 2019-04-04 17:04:30
categories: arXiv_CL
tags: arXiv_CL Adversarial
author: Nelson F. Liu, Roy Schwartz, Noah A. Smith
mathjax: true
---

* content
{:toc}

##### Abstract
Several datasets have recently been constructed to expose brittleness in models trained on existing benchmarks. While model performance on these challenge datasets is significantly lower compared to the original benchmark, it is unclear what particular weaknesses they reveal. For example, a challenge dataset may be difficult because it targets phenomena that current models cannot capture, or because it simply exploits blind spots in a model's specific training set. We introduce inoculation by fine-tuning, a new analysis method for studying challenge datasets by exposing models (the metaphorical patient) to a small amount of data from the challenge dataset (a metaphorical pathogen) and assessing how well they can adapt. We apply our method to analyze the NLI "stress tests" (Naik et al., 2018) and the Adversarial SQuAD dataset (Jia and Liang, 2017). We show that after slight exposure, some of these datasets are no longer challenging, while others remain difficult. Our results indicate that failures on challenge datasets may lead to very different conclusions about models, training datasets, and the challenge datasets themselves.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.02668](http://arxiv.org/abs/1904.02668)

##### PDF
[http://arxiv.org/pdf/1904.02668](http://arxiv.org/pdf/1904.02668)

