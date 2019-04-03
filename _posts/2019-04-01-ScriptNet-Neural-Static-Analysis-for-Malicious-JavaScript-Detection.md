---
layout: post
title: "ScriptNet: Neural Static Analysis for Malicious JavaScript Detection"
date: 2019-04-01 22:00:57
categories: arXiv_AI
tags: arXiv_AI Embedding Detection
author: Jack W. Stokes, Rakshit Agrawal, Geoff McDonald, Matthew Hausknecht
mathjax: true
---

* content
{:toc}

##### Abstract
Malicious scripts are an important computer infection threat vector in the wild. For web-scale processing, static analysis offers substantial computing efficiencies. We propose the ScriptNet system for neural malicious JavaScript detection which is based on static analysis. We use the Convoluted Partitioning of Long Sequences (CPoLS) model, which processes Javascript files as byte sequences. Lower layers capture the sequential nature of these byte sequences while higher layers classify the resulting embedding as malicious or benign. Unlike previously proposed solutions, our model variants are trained in an end-to-end fashion allowing discriminative training even for the sequential processing layers. Evaluating this model on a large corpus of 212,408 JavaScript files indicates that the best performing CPoLS model offers a 97.20% true positive rate (TPR) for the first 60K byte subsequence at a false positive rate (FPR) of 0.50%. The best performing CPoLS model significantly outperform several baseline models.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.01126](http://arxiv.org/abs/1904.01126)

##### PDF
[http://arxiv.org/pdf/1904.01126](http://arxiv.org/pdf/1904.01126)

