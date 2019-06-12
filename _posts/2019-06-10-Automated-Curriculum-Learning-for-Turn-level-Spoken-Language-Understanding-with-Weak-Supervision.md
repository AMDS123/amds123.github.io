---
layout: post
title: "Automated Curriculum Learning for Turn-level Spoken Language Understanding with Weak Supervision"
date: 2019-06-10 21:54:33
categories: arXiv_CL
tags: arXiv_CL
author: Hao Lang, Wen Wang
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a learning approach for turn-level spoken language understanding, which facilitates a user to speak one or more utterances compositionally in a turn for completing a task (e.g., voice ordering). A typical pipelined approach for these understanding tasks requires non-trivial annotation effort for developing its multiple components. Also, the pipeline is difficult to port to a new domain or scale up. To address these problems, we propose an end-to-end statistical model with weak supervision. We employ randomized beam search with memory augmentation (RBSMA) to solve complicated problems for which long promising trajectories are usually difficult to explore. Furthermore, considering the diversity of problem complexity, we explore automated curriculum learning (CL) for weak supervision to accelerate exploration and learning. We evaluate the proposed approach on real-world user logs of a commercial voice ordering system. Results demonstrate that when trained on a small number of end-to-end annotated sessions collected with low cost, our model performs comparably to the deployed pipelined system, saving the development labor over an order of magnitude. The RBSMA algorithm improves the test set accuracy by 7.8% relative compared to the standard beam search. Automated CL leads to better generalization and further improves the test set accuracy by 5% relative.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.04291](http://arxiv.org/abs/1906.04291)

##### PDF
[http://arxiv.org/pdf/1906.04291](http://arxiv.org/pdf/1906.04291)

