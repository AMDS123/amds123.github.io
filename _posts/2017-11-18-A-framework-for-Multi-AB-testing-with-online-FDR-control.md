---
layout: post
title: "A framework for Multi-A/B testing with online FDR control"
date: 2017-11-18 07:25:12
categories: arXiv_CV
tags: arXiv_CV Caption
author: Fanny Yang, Aaditya Ramdas, Kevin Jamieson, Martin J. Wainwright
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an alternative framework to existing setups for controlling false alarms when multiple A/B tests are run over time. This setup arises in many practical applications, e.g. when pharmaceutical companies test new treatment options against control pills for different diseases, or when internet companies test their default webpages versus various alternatives over time. Our framework proposes to replace a sequence of A/B tests by a sequence of best-arm MAB instances, which can be continuously monitored by the data scientist. When interleaving the MAB tests with an an online false discovery rate (FDR) algorithm, we can obtain the best of both worlds: low sample complexity and any time online FDR control. Our main contributions are: (i) to propose reasonable definitions of a null hypothesis for MAB instances; (ii) to demonstrate how one can derive an always-valid sequential p-value that allows continuous monitoring of each MAB test; and (iii) to show that using rejection thresholds of online-FDR algorithms as the confidence levels for the MAB algorithms results in both sample-optimality, high power and low FDR at any point in time. We run extensive simulations to verify our claims, and also report results on real data collected from the New Yorker Cartoon Caption contest.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1706.05378](https://arxiv.org/abs/1706.05378)

##### PDF
[https://arxiv.org/pdf/1706.05378](https://arxiv.org/pdf/1706.05378)

