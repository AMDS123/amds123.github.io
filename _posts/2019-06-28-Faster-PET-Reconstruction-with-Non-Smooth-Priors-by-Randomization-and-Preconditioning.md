---
layout: post
title: "Faster PET Reconstruction with Non-Smooth Priors by Randomization and Preconditioning"
date: 2019-06-28 17:28:26
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Matthias J. Ehrhardt, Pawel Markiewicz, Carola-Bibiane Sch&#xf6;nlieb
mathjax: true
---

* content
{:toc}

##### Abstract
Uncompressed clinical data from modern positron emission tomography (PET) scanners are very large, exceeding 350 million data points (projection bins). The last decades have seen tremendous advancements in mathematical imaging tools many of which lead to non-smooth (i.e. non-differentiable) optimization problems which are much harder to solve than smooth optimization problems. Most of these tools have not been translated to clinical PET data, as the state-of-the-art algorithms for non-smooth problems do not scale well to large data. In this work, inspired by big data machine learning applications, we use advanced randomized optimization algorithms to solve the PET reconstruction problem for a very large class of non-smooth priors which includes for example total variation, total generalized variation, directional total variation and various different physical constraints. The proposed algorithm randomly uses subsets of the data and only updates the variables associated with these. While this idea often leads to divergent algorithms, we show that the proposed algorithm does indeed converge for any proper subset selection. Numerically, we show on real PET data (FDG and florbetapir) from a Siemens Biograph mMR that about ten projections and backprojections are sufficient to solve the MAP optimisation problem related to many popular non-smooth priors; thus showing that the proposed algorithm is fast enough to bring these models into routine clinical practice.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1808.07150](http://arxiv.org/abs/1808.07150)

##### PDF
[http://arxiv.org/pdf/1808.07150](http://arxiv.org/pdf/1808.07150)

