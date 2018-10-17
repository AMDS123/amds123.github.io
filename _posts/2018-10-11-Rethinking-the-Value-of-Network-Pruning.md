---
layout: post
title: "Rethinking the Value of Network Pruning"
date: 2018-10-11 22:15:28
categories: arXiv_CV
tags: arXiv_CV
author: Zhuang Liu, Mingjie Sun, Tinghui Zhou, Gao Huang, Trevor Darrell
mathjax: true
---

* content
{:toc}

##### Abstract
Network pruning is widely used for reducing the heavy computational cost of deep models. A typical pruning algorithm is a three-stage pipeline, i.e., training (a large model), pruning and fine-tuning. During pruning, according to a certain criterion, redundant weights are pruned and important weights are kept to best preserve the accuracy. In this work, we make several surprising observations which contradict common beliefs. For all the six state-of-the-art pruning algorithms we examined, fine-tuning a pruned model only gives comparable or even worse performance than training that model with randomly initialized weights. For pruning algorithms which assume a predefined target network architecture, one can get rid of the full pipeline and directly train the target network from scratch. Our observations are consistent for a wide variety of pruning algorithms with multiple network architectures, datasets, and tasks. Our results have several implications: 1) training a large, over-parameterized model is not necessary to obtain an efficient final model, 2) learned "important" weights of the large model are not necessarily useful for the small pruned model, 3) the pruned architecture itself, rather than a set of inherited "important" weights, is what leads to the efficiency benefit in the final model, which suggests that some pruning algorithms could be seen as performing network architecture search.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.05270](https://arxiv.org/abs/1810.05270)

##### PDF
[https://arxiv.org/pdf/1810.05270](https://arxiv.org/pdf/1810.05270)

