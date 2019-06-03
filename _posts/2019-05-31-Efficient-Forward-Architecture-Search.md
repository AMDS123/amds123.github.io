---
layout: post
title: "Efficient Forward Architecture Search"
date: 2019-05-31 00:10:17
categories: arXiv_CV
tags: arXiv_CV NAS
author: Hanzhang Hu, John Langford, Rich Caruana, Saurajit Mukherjee, Eric Horvitz, Debadeepta Dey
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a neural architecture search (NAS) algorithm, Petridish, to iteratively add shortcut connections to existing network layers. The added shortcut connections effectively perform gradient boosting on the augmented layers. The proposed algorithm is motivated by the feature selection algorithm forward stage-wise linear regression, since we consider NAS as a generalization of feature selection for regression, where NAS selects shortcuts among layers instead of selecting features. In order to reduce the number of trials of possible connection combinations, we train jointly all possible connections at each stage of growth while leveraging feature selection techniques to choose a subset of them. We experimentally show this process to be an efficient forward architecture search algorithm that can find competitive models using few GPU days in both the search space of repeatable network modules (cell-search) and the space of general networks (macro-search). Petridish is particularly well-suited for warm-starting from existing models crucial for lifelong-learning scenarios.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.13360](https://arxiv.org/abs/1905.13360)

##### PDF
[https://arxiv.org/pdf/1905.13360](https://arxiv.org/pdf/1905.13360)

