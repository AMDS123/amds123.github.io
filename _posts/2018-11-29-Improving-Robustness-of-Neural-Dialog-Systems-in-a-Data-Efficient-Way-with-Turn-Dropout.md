---
layout: post
title: "Improving Robustness of Neural Dialog Systems in a Data-Efficient Way with Turn Dropout"
date: 2018-11-29 14:03:00
categories: arXiv_CL
tags: arXiv_CL Object_Detection Detection
author: Igor Shalyminov, Sungjin Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Neural network-based dialog models often lack robustness to anomalous, out-of-domain (OOD) user input which leads to unexpected dialog behavior and thus considerably limits such models' usage in mission-critical production environments. The problem is especially relevant in the setting of dialog system bootstrapping with limited training data and no access to OOD examples. In this paper, we explore the problem of robustness of such systems to anomalous input and the associated to it trade-off in accuracies on seen and unseen data. We present a new dataset for studying the robustness of dialog systems to OOD input, which is bAbI Dialog Task 6 augmented with OOD content in a controlled way. We then present turn dropout, a simple yet efficient negative sampling-based technique for improving robustness of neural dialog models. We demonstrate its effectiveness applied to Hybrid Code Network-family models (HCNs) which reach state-of-the-art results on our OOD-augmented dataset as well as the original one. Specifically, an HCN trained with turn dropout achieves state-of-the-art performance of more than 75% per-utterance accuracy on the augmented dataset's OOD turns and 74% F1-score as an OOD detector. Furthermore, we introduce a Variational HCN enhanced with turn dropout which achieves more than 56.5% accuracy on the original bAbI Task 6 dataset, thus outperforming the initially reported HCN's result.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.12148](http://arxiv.org/abs/1811.12148)

##### PDF
[http://arxiv.org/pdf/1811.12148](http://arxiv.org/pdf/1811.12148)

