---
layout: post
title: "Multiclass segmentation as multitask learning for drusen segmentation in retinal optical coherence tomography"
date: 2019-06-18 16:45:46
categories: arXiv_CV
tags: arXiv_CV Regularization Segmentation Face
author: Rhona Asgari, Jos&#xe9; Ignacio Orlando, Sebastian Waldstein, Ferdinand Schlanitz, Magdalena Baratsits, Ursula Schmidt-Erfurth, Hrvoje Bogunovi&#x107;
mathjax: true
---

* content
{:toc}

##### Abstract
Automated drusen segmentation in retinal optical coherence tomography (OCT) scans is relevant for understanding age-related macular degeneration (AMD) risk and progression. This task is usually performed by segmenting the top/bottom anatomical interfaces that define drusen, the outer boundary of the retinal pigment epithelium (OBRPE) and the Bruch's membrane (BM), respectively. In this paper we propose a novel multi-decoder architecture that tackles drusen segmentation as a multitask problem. Instead of training a multiclass model for OBRPE/BM segmentation, we use one decoder per target class and an extra one aiming for the area between the layers. We also introduce connections between each class-specific branch and the additional decoder to increase the regularization effect of this surrogate task. We validated our approach on private/public data sets with 166 early/intermediate AMD Spectralis, and 200 AMD and control Bioptigen OCT volumes, respectively. Our method consistently outperformed several baselines in both layer and drusen segmentation evaluations.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.07679](http://arxiv.org/abs/1906.07679)

##### PDF
[http://arxiv.org/pdf/1906.07679](http://arxiv.org/pdf/1906.07679)

