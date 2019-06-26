---
layout: post
title: "Learning a sparse database for patch-based medical image segmentation"
date: 2019-06-25 06:16:05
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation Optimization
author: Moti Freiman, Hannes Nickisch, Holger Schmitt, Pal Maurovich-Horvat, Patrick Donnelly, Mani Vembar, Liran Goshen
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a functional for the learning of an optimal database for patch-based image segmentation with application to coronary lumen segmentation from coronary computed tomography angiography (CCTA) data. The proposed functional consists of fidelity, sparseness and robustness to small-variations terms and their associated weights. Existing work address database optimization by prototype selection aiming to optimize the database by either adding or removing prototypes according to a set of predefined rules. In contrast, we formulate the database optimization task as an energy minimization problem that can be solved using standard numerical tools. We apply the proposed database optimization functional to the task of optimizing a database for patch-base coronary lumen segmentation. Our experiments using the publicly available MICCAI 2012 coronary lumen segmentation challenge data show that optimizing the database using the proposed approach reduced database size by 96% while maintaining the same level of lumen segmentation accuracy. Moreover, we show that the optimized database yields an improved specificity of CCTA based fractional flow reserve (0.73 vs 0.7 for all lesions and 0.68 vs 0.65 for obstructive lesions) using a training set of 132 (76 obstructive) coronary lesions with invasively measured FFR as the reference.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.10338](http://arxiv.org/abs/1906.10338)

##### PDF
[http://arxiv.org/pdf/1906.10338](http://arxiv.org/pdf/1906.10338)

