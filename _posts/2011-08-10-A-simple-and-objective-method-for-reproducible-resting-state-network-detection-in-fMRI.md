---
layout: post
title: "A simple and objective method for reproducible resting state network detection in fMRI"
date: 2011-08-10 19:02:29
categories: arXiv_CV
tags: arXiv_CV Detection
author: Gautam V. Pendse, David Borsook, Lino Becerra
mathjax: true
---

* content
{:toc}

##### Abstract
Spatial Independent Component Analysis (ICA) decomposes the time by space functional MRI (fMRI) matrix into a set of 1-D basis time courses and their associated 3-D spatial maps that are optimized for mutual independence. When applied to resting state fMRI (rsfMRI), ICA produces several spatial independent components (ICs) that seem to have biological relevance - the so-called resting state networks (RSNs). The ICA problem is well posed when the true data generating process follows a linear mixture of ICs model in terms of the identifiability of the mixing matrix. However, the contrast function used for promoting mutual independence in ICA is dependent on the finite amount of observed data and is potentially non-convex with multiple local minima. Hence, each run of ICA could produce potentially different IC estimates even for the same data. One technique to deal with this run-to-run variability of ICA was proposed by Yang et al. (2008) in their algorithm RAICAR which allows for the selection of only those ICs that have a high run-to-run reproducibility. We propose an enhancement to the original RAICAR algorithm that enables us to assign reproducibility p-values to each IC and allows for an objective assessment of both within subject and across subjects reproducibility. We call the resulting algorithm RAICAR-N (N stands for null hypothesis test), and we have applied it to publicly available human rsfMRI data (this http URL). Our reproducibility analyses indicated that many of the published RSNs in rsfMRI literature are highly reproducible. However, we found several other RSNs that are highly reproducible but not frequently listed in the literature.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1108.2248](https://arxiv.org/abs/1108.2248)

##### PDF
[https://arxiv.org/pdf/1108.2248](https://arxiv.org/pdf/1108.2248)

