---
layout: post
title: "Progressive Cluster Purification for Transductive Few-shot Learning"
date: 2019-06-10 08:55:37
categories: arXiv_CV
tags: arXiv_CV Inference Classification Relation
author: Chenyang Si, Wentao Chen, Wei Wang, Liang Wang, Tieniu Tan
mathjax: true
---

* content
{:toc}

##### Abstract
Few-shot learning aims to learn to generalize a classifier to novel classes with limited labeled data. Transductive inference that utilizes unlabeled test set to deal with low-data problem has been employed for few-shot learning in recent literature. Yet, these methods do not explicitly exploit the manifold structures of semantic clusters, which is inefficient for transductive inference. In this paper, we propose a novel Progressive Cluster Purification (PCP) method for transductive few-shot learning. The PCP can progressively purify the cluster by exploring the semantic interdependency in the individual cluster space. Specifically, the PCP consists of two-level operations: inter-class classification and intra-class transduction. The inter-class classification partitions all the test samples into several clusters by comparing the test samples with the prototypes. The intra-class transduction effectively explores trustworthy test samples for each cluster by modeling data relations within a cluster as well as among different clusters. Then, it refines the prototypes to better represent the real distribution of semantic clusters. The refined prototypes are used to remeasure all the test instances and purify each cluster. Furthermore, the inter-class classification and the intra-class transduction are extremely flexible to be repeated several times to progressively purify the clusters. Experimental results are provided on two datasets: miniImageNet dataset and tieredImageNet dataset. The comparison results demonstrate the effectiveness of our approach and show that our approach outperforms the state-of-the-art methods on both datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.03847](http://arxiv.org/abs/1906.03847)

##### PDF
[http://arxiv.org/pdf/1906.03847](http://arxiv.org/pdf/1906.03847)

