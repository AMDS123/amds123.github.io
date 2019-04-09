---
layout: post
title: "Long-Term Vehicle Localization by Recursive Knowledge Distillation"
date: 2019-04-07 00:16:51
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN Recognition
author: Hiroki Tomoe, Tanaka Kanji
mathjax: true
---

* content
{:toc}

##### Abstract
Most of the current state-of-the-art frameworks for cross-season visual place recognition (CS-VPR) focus on domain adaptation (DA) to a single specific season. From the viewpoint of long-term CS-VPR, such frameworks do not scale well to sequential multiple domains (e.g., spring - summer - autumn - winter - ... ). The goal of this study is to develop a novel long-term ensemble learning (LEL) framework that allows for a constant cost retraining in long-term sequential-multi-domain CS-VPR (SMD-VPR), which only requires the memorization of a small constant number of deep convolutional neural networks (CNNs) and can retrain the CNN ensemble of every season at a small constant time/space cost. We frame our task as the multi-teacher multi-student knowledge distillation (MTMS-KD), which recursively compresses all the previous season's knowledge into a current CNN ensemble. We further address the issue of teacher-student-assignment (TSA) to achieve a good generalization/specialization tradeoff. Experimental results on SMD-VPR tasks validate the efficacy of the proposed approach.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.03551](http://arxiv.org/abs/1904.03551)

##### PDF
[http://arxiv.org/pdf/1904.03551](http://arxiv.org/pdf/1904.03551)

