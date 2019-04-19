---
layout: post
title: "Unsupervised Open Domain Recognition by Semantic Discrepancy Minimization"
date: 2019-04-18 08:13:54
categories: arXiv_CV
tags: arXiv_CV Embedding Classification Recognition
author: Junbao Zhuo, Shuhui Wang, Shuhao Cui, Qingming Huang
mathjax: true
---

* content
{:toc}

##### Abstract
We address the unsupervised open domain recognition (UODR) problem, where categories in labeled source domain S is only a subset of those in unlabeled target domain T. The task is to correctly classify all samples in T including known and unknown categories. UODR is challenging due to the domain discrepancy, which becomes even harder to bridge when a large number of unknown categories exist in T. Moreover, the classification rules propagated by graph CNN (GCN) may be distracted by unknown categories and lack generalization capability. To measure the domain discrepancy for asymmetric label space between S and T, we propose Semantic-Guided Matching Discrepancy (SGMD), which first employs instance matching between S and T, and then the discrepancy is measured by a weighted feature distance between matched instances. We further design a limited balance constraint to achieve a more balanced classification output on known and unknown categories. We develop Unsupervised Open Domain Transfer Network (UODTN), which learns both the backbone classification network and GCN jointly by reducing the SGMD, enforcing the limited balance constraint and minimizing the classification loss on S. UODTN better preserves the semantic structure and enforces the consistency between the learned domain invariant visual features and the semantic embeddings. Experimental results show superiority of our method on recognizing images of both known and unknown categories.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08631](http://arxiv.org/abs/1904.08631)

##### PDF
[http://arxiv.org/pdf/1904.08631](http://arxiv.org/pdf/1904.08631)

