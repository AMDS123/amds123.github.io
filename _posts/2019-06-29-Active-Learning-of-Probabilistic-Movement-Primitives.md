---
layout: post
title: "Active Learning of Probabilistic Movement Primitives"
date: 2019-06-29 21:01:57
categories: arXiv_RO
tags: arXiv_RO
author: Adam Conkey, Tucker Hermans
mathjax: true
---

* content
{:toc}

##### Abstract
A Probabilistic Movement Primitive (ProMP) defines a distribution over trajectories with an associated feedback policy. ProMPs are typically initialized from human demonstrations and achieve task generalization through probabilistic operations. However, there is currently no principled guidance in the literature to determine how many demonstrations a teacher should provide and what constitutes a "good'" demonstration for promoting generalization. In this paper, we present an active learning approach to learning a library of ProMPs capable of task generalization over a given space. We utilize uncertainty sampling techniques to generate a task instance for which a teacher should provide a demonstration. The provided demonstration is incorporated into an existing ProMP if possible, or a new ProMP is created from the demonstration if it is determined that it is too dissimilar from existing demonstrations. We provide a qualitative comparison between common active learning metrics; motivated by this comparison we present a novel uncertainty sampling approach named "Greatest Mahalanobis Distance.'' We perform grasping experiments on a real KUKA robot and show our novel active learning measure achieves better task generalization with fewer demonstrations than a random sampling over the space.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.00277](http://arxiv.org/abs/1907.00277)

##### PDF
[http://arxiv.org/pdf/1907.00277](http://arxiv.org/pdf/1907.00277)

