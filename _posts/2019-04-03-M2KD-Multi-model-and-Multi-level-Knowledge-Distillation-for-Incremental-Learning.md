---
layout: post
title: "M2KD: Multi-model and Multi-level Knowledge Distillation for Incremental Learning"
date: 2019-04-03 04:54:01
categories: arXiv_CV
tags: arXiv_CV Knowledge
author: Peng Zhou, Long Mai, Jianming Zhang, Ning Xu, Zuxuan Wu, Larry S. Davis
mathjax: true
---

* content
{:toc}

##### Abstract
Incremental learning targets at achieving good performance on new categories without forgetting old ones. Knowledge distillation has been shown critical in preserving the performance on old classes. Conventional methods, however, sequentially distill knowledge only from the last model, leading to performance degradation on the old classes in later incremental learning steps. In this paper, we propose a multi-model and multi-level knowledge distillation strategy. Instead of sequentially distilling knowledge only from the last model, we directly leverage all previous model snapshots. In addition, we incorporate an auxiliary distillation to further preserve knowledge encoded at the intermediate feature levels. To make the model more memory efficient, we adapt mask based pruning to reconstruct all previous models with a small memory footprint. Experiments on standard incremental learning benchmarks show that our method preserves the knowledge on old classes better and improves the overall performance over standard distillation techniques.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1904.01769](https://arxiv.org/abs/1904.01769)

##### PDF
[https://arxiv.org/pdf/1904.01769](https://arxiv.org/pdf/1904.01769)

