---
layout: post
title: "A Novel Re-weighting Method for Connectionist Temporal Classification"
date: 2019-04-24 02:50:29
categories: arXiv_CV
tags: arXiv_CV Classification Recognition
author: Hongzhu Li, Weiqiang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
The connectionist temporal classification (CTC) enables end-to-end sequence learning by maximizing the probability of correctly recognizing sequences during training. With an extra $blank$ class, the CTC implicitly converts recognizing a sequence into classifying each timestep within the sequence. But the CTC loss is not intuitive for such classification task, so the class imbalance within each sequence, caused by the overwhelming $blank$ timesteps, is a knotty problem. In this paper, we define a piece-wise function as the pseudo ground-truth to reinterpret the CTC loss based on sequences as the cross entropy loss based on timesteps. The cross entropy form makes it easy to re-weight the CTC loss. Experiments on text recognition show that the weighted CTC loss solves the class imbalance problem as well as facilitates the convergence, generally leading to better results than the CTC loss. Beside this, the reinterpretation of CTC, as a brand new perspective, may be potentially useful in some other situations.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.10619](http://arxiv.org/abs/1904.10619)

##### PDF
[http://arxiv.org/pdf/1904.10619](http://arxiv.org/pdf/1904.10619)

