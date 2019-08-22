---
layout: post
title: "Communal Domain Learning for Registration in Drifted Image Spaces"
date: 2019-08-20 23:50:56
categories: arXiv_CV
tags: arXiv_CV Represenation_Learning Optimization
author: Awais Mansoor, Marius George Linguraru
mathjax: true
---

* content
{:toc}

##### Abstract
Designing a registration framework for images that do not share the same probability distribution is a major challenge in modern image analytics yet trivial task for the human visual system (HVS). Discrepancies in probability distributions, also known as \emph{drifts}, can occur due to various reasons including, but not limited to differences in sequences and modalities (e.g., MRI T1-T2 and MRI-CT registration), or acquisition settings (e.g., multisite, inter-subject, or intra-subject registrations). The popular assumption about the working of HVS is that it exploits a communal feature subspace exists between the registering images or fields-of-view that encompasses key drift-invariant features. Mimicking the approach that is potentially adopted by the HVS, herein, we present a representation learning technique of this invariant communal subspace that is shared by registering domains. The proposed communal domain learning (CDL) framework uses a set of hierarchical nonlinear transforms to learn the communal subspace that minimizes the probability differences and maximizes the amount of shared information between the registering domains. Similarity metric and parameter optimization calculations for registration are subsequently performed in the drift-minimized learned communal subspace. This generic registration framework is applied to register multisequence (MR: T1, T2) and multimodal (MR, CT) images. Results demonstrated generic applicability, consistent performance, and statistically significant improvement for both multi-sequence and multi-modal data using the proposed approach ($p$-value$&lt;0.001$; Wilcoxon rank sum test) over baseline methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.07646](http://arxiv.org/abs/1908.07646)

##### PDF
[http://arxiv.org/pdf/1908.07646](http://arxiv.org/pdf/1908.07646)

