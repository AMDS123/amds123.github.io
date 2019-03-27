---
layout: post
title: "Unifying Unsupervised Domain Adaptation and Zero-Shot Visual Recognition"
date: 2019-03-25 21:34:39
categories: arXiv_CV
tags: arXiv_CV Knowledge Classification Recognition
author: Qian Wang, Penghui Bu, Toby P. Breckon
mathjax: true
---

* content
{:toc}

##### Abstract
Unsupervised domain adaptation aims to transfer knowledge from a source domain to a target domain so that the target domain data can be recognized without any explicit labelling information for this domain. One limitation of the problem setting is that testing data, despite having no labels, from the target domain is needed during training, which prevents the trained model being directly applied to classify unseen test instances. We formulate a new cross-domain classification problem arising from real-world scenarios where labelled data is available for a subset of classes (known classes) in the target domain, and we expect to recognize new samples belonging to any class (known and unseen classes) once the model is learned. This is a generalized zero-shot learning problem where the side information comes from the source domain in the form of labelled samples instead of class-level semantic representations commonly used in traditional zero-shot learning. We present a unified domain adaptation framework for both unsupervised and zero-shot learning conditions. Our approach learns a joint subspace from source and target domains so that the projections of both data in the subspace can be domain invariant and easily separable. We use the supervised locality preserving projection (SLPP) as the enabling technique and conduct experiments under both unsupervised and zero-shot learning conditions, achieving state-of-the-art results on three domain adaptation benchmark datasets: Office-Caltech, Office31 and Office-Home.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.10601](http://arxiv.org/abs/1903.10601)

##### PDF
[http://arxiv.org/pdf/1903.10601](http://arxiv.org/pdf/1903.10601)

