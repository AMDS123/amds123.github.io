---
layout: post
title: "Linear solution to the minimal absolute pose rolling shutter problem"
date: 2018-12-30 13:43:59
categories: arXiv_CV
tags: arXiv_CV
author: Zuzana Kukelova, Cenek Albl, Akihiro Sugimoto, Tomas Pajdla
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents new efficient solutions to the rolling shutter camera absolute pose problem. Unlike the state-of-the-art polynomial solvers, we approach the problem using simple and fast linear solvers in an iterative scheme. We present several solutions based on fixing different sets of variables and investigate the performance of them thoroughly. We design a new alternation strategy that estimates all parameters in each iteration linearly by fixing just the non-linear terms. Our best 6-point solver, based on the new alternation technique, shows an identical or even better performance than the state-of-the-art R6P solver and is two orders of magnitude faster. In addition, a linear non-iterative solver is presented that requires a non-minimal number of 9 correspondences but provides even better results than the state-of-the-art R6P. Moreover, all proposed linear solvers provide a single solution while the state-of-the-art R6P provides up to 20 solutions which have to be pruned by expensive verification.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.11532](http://arxiv.org/abs/1812.11532)

##### PDF
[http://arxiv.org/pdf/1812.11532](http://arxiv.org/pdf/1812.11532)

