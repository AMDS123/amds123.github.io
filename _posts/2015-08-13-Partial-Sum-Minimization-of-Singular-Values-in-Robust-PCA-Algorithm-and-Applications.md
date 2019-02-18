---
layout: post
title: "Partial Sum Minimization of Singular Values in Robust PCA: Algorithm and Applications"
date: 2015-08-13 12:51:08
categories: arXiv_AI
tags: arXiv_AI Sparse Detection
author: Tae-Hyun Oh, Yu-Wing Tai, Jean-Charles Bazin, Hyeongwoo Kim, In So Kweon
mathjax: true
---

* content
{:toc}

##### Abstract
Robust Principal Component Analysis (RPCA) via rank minimization is a powerful tool for recovering underlying low-rank structure of clean data corrupted with sparse noise/outliers. In many low-level vision problems, not only it is known that the underlying structure of clean data is low-rank, but the exact rank of clean data is also known. Yet, when applying conventional rank minimization for those problems, the objective function is formulated in a way that does not fully utilize a priori target rank information about the problems. This observation motivates us to investigate whether there is a better alternative solution when using rank minimization. In this paper, instead of minimizing the nuclear norm, we propose to minimize the partial sum of singular values, which implicitly encourages the target rank constraint. Our experimental analyses show that, when the number of samples is deficient, our approach leads to a higher success rate than conventional rank minimization, while the solutions obtained by the two approaches are almost identical when the number of samples is more than sufficient. We apply our approach to various low-level vision problems, e.g. high dynamic range imaging, motion edge detection, photometric stereo, image alignment and recovery, and show that our results outperform those obtained by the conventional nuclear norm rank minimization method.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1503.01444](http://arxiv.org/abs/1503.01444)

##### PDF
[http://arxiv.org/pdf/1503.01444](http://arxiv.org/pdf/1503.01444)

