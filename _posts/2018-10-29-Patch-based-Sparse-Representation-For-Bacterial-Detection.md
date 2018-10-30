---
layout: post
title: "Patch-based Sparse Representation For Bacterial Detection"
date: 2018-10-29 10:31:06
categories: arXiv_CV
tags: arXiv_CV Sparse Detection Relation
author: Ahmed Karam Eldaly, Yoann Altmann, Ahsan Akram, Antonios Perperidis, Kevin Dhaliwal, Stephen McLaughlin
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a supervised approach for bacterial detection in optical endomicroscopy images. This approach splits each image into a set of overlapping patches and assumes that observed intensities are linear combinations of the actual intensity values associated with background image structures, corrupted by additive Gaussian noise and potentially by a sparse outlier term modelling anomalies (which are considered to be candidate bacteria). The actual intensity term representing background structures is modelled as a linear combination of a few atoms drawn from a dictionary which is learned from bacteria-free data and then fixed while analyzing new images. The bacteria detection task is formulated as a minimization problem and an Alternating Direction Method of Multipliers (ADMM) is then used to estimate the unknown parameters. Simulations conducted using two ex vivo lung datasets show good detection and correlation performance between bacteria counts identified by a trained clinician and those of the proposed method.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.12043](http://arxiv.org/abs/1810.12043)

##### PDF
[http://arxiv.org/pdf/1810.12043](http://arxiv.org/pdf/1810.12043)

