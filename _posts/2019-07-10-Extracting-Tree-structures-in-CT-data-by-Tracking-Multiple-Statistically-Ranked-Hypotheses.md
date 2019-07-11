---
layout: post
title: "Extracting Tree-structures in CT data by Tracking Multiple Statistically Ranked Hypotheses"
date: 2019-07-10 15:23:20
categories: arXiv_CV
tags: arXiv_CV Segmentation Tracking
author: Raghavendra Selvan, Jens Petersen, Jesper H Pedersen, Marleen de Bruijne
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we adapt a method based on multiple hypothesis tracking (MHT) that has been shown to give state-of-the-art vessel segmentation results in interactive settings, for the purpose of extracting trees. Regularly spaced tubular templates are fit to image data forming local hypotheses. These local hypotheses are used to construct the MHT tree, which is then traversed to make segmentation decisions. However, some critical parameters in this method are scale-dependent and have an adverse effect when tracking structures of varying dimensions. We propose to use statistical ranking of local hypotheses in constructing the MHT tree, which yields a probabilistic interpretation of scores across scales and helps alleviate the scale-dependence of MHT parameters. This enables our method to track trees starting from a single seed point. Our method is evaluated on chest CT data to extract airway trees and coronary arteries. In both cases, we show that our method performs significantly better than the original MHT method.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1806.08981](http://arxiv.org/abs/1806.08981)

##### PDF
[http://arxiv.org/pdf/1806.08981](http://arxiv.org/pdf/1806.08981)

