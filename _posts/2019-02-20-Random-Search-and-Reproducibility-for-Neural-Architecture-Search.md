---
layout: post
title: "Random Search and Reproducibility for Neural Architecture Search"
date: 2019-02-20 16:49:07
categories: arXiv_CV
tags: arXiv_CV NAS Optimization
author: Liam Li, Ameet Talwalkar
mathjax: true
---

* content
{:toc}

##### Abstract
Neural architecture search (NAS) is a promising research direction that has the potential to replace expert-designed networks with learned, task-specific architectures. In this work, in order to help ground the empirical results in this field, we propose new NAS baselines that build off the following observations: (i) NAS is a specialized hyperparameter optimization problem; and (ii) random search is a competitive baseline for hyperparameter optimization. Leveraging these observations, we evaluate both random search with early-stopping and a novel random search with weight-sharing algorithm on two standard NAS benchmarks---PTB and CIFAR-10. Our results show that random search with early-stopping is a competitive NAS baseline, e.g., it performs at least as well as ENAS, a leading NAS method, on both benchmarks. Additionally, random search with weight-sharing outperforms random search with early-stopping, achieving a state-of-the-art NAS result on PTB and a highly competitive result on CIFAR-10. Finally, we explore the existing reproducibility issues of published NAS results. We note the lack of source material needed to exactly reproduce these results, and further discuss the robustness of published results given the various sources of variability in NAS experimental setups. Relatedly, we provide all information (code, random seeds, documentation) needed to exactly reproduce our results, and report our random search with weight-sharing results for each benchmark on two independent experimental runs.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1902.07638](https://arxiv.org/abs/1902.07638)

##### PDF
[https://arxiv.org/pdf/1902.07638](https://arxiv.org/pdf/1902.07638)

