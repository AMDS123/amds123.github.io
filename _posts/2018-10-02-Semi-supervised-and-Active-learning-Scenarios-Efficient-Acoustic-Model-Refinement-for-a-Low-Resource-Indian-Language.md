---
layout: post
title: "Semi-supervised and Active-learning Scenarios: Efficient Acoustic Model Refinement for a Low Resource Indian Language"
date: 2018-10-02 07:23:42
categories: arXiv_CV
tags: arXiv_CV
author: Maharajan Chellapriyadharshini, Anoop Toffy, Srinivasa Raghavan K. M., V Ramasubramanian
mathjax: true
---

* content
{:toc}

##### Abstract
We address the problem of efficient acoustic-model refinement (continuous retraining) using semi-supervised and active learning for a low resource Indian language, wherein the low resource constraints are having i) a small labeled corpus from which to train a baseline `seed' acoustic model and ii) a large training corpus without orthographic labeling or from which to perform a data selection for manual labeling at low costs. The proposed semi-supervised learning decodes the unlabeled large training corpus using the seed model and through various protocols, selects the decoded utterances with high reliability using confidence levels (that correlate to the WER of the decoded utterances) and iterative bootstrapping. The proposed active learning protocol uses confidence level based metric to select the decoded utterances from the large unlabeled corpus for further labeling. The semi-supervised learning protocols can offer a WER reduction, from a poorly trained seed model, by as much as 50% of the best WER-reduction realizable from the seed model's WER, if the large corpus were labeled and used for acoustic-model training. The active learning protocols allow that only 60% of the entire training corpus be manually labeled, to reach the same performance as the entire data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.06635](http://arxiv.org/abs/1810.06635)

##### PDF
[http://arxiv.org/pdf/1810.06635](http://arxiv.org/pdf/1810.06635)

