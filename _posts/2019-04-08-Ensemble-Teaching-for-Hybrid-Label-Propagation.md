---
layout: post
title: "Ensemble Teaching for Hybrid Label Propagation"
date: 2019-04-08 04:10:40
categories: arXiv_CV
tags: arXiv_CV Knowledge Optimization
author: Chen Gong, Dacheng Tao, Xiaojun Chang, Jian Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Label propagation aims to iteratively diffuse the label information from labeled examples to unlabeled examples over a similarity graph. Current label propagation algorithms cannot consistently yield satisfactory performance due to two reasons: one is the instability of single propagation method in dealing with various practical data, and the other one is the improper propagation sequence ignoring the labeling difficulties of different examples. To remedy above defects, this paper proposes a novel propagation algorithm called hybrid diffusion under ensemble teaching (HyDEnT). Specifically, HyDEnT integrates multiple propagation methods as base learners to fully exploit their individual wisdom, which helps HyDEnT to be stable and obtain consistent encouraging results. More importantly, HyDEnT conducts propagation under the guidance of an ensemble of teachers. That is to say, in every propagation round the simplest curriculum examples are wisely designated by a teaching algorithm, so that their labels can be reliably and accurately decided by the learners. To optimally choose these simplest examples, every teacher in the ensemble should comprehensively consider the examples' difficulties from its own viewpoint, as well as the common knowledge shared by all the teachers. This is accomplished by a designed optimization problem, which can be efficiently solved via the block coordinate descent method. Thanks to the efforts of the teachers, all the unlabeled examples are logically propagated from simple to difficult, leading to better propagation quality of HyDEnT than the existing methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.03828](http://arxiv.org/abs/1904.03828)

##### PDF
[http://arxiv.org/pdf/1904.03828](http://arxiv.org/pdf/1904.03828)

