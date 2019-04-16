---
layout: post
title: "Part-Aware Fine-grained Object Categorization using Weakly Supervised Part Detection Network"
date: 2018-06-16 07:08:59
categories: arXiv_CV
tags: arXiv_CV Object_Detection Weakly_Supervised Classification Prediction Detection
author: Yabin Zhang, Kui Jia, Zhixin Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Fine-grained object categorization aims for distinguishing objects of subordinate categories that belong to the same entry-level object category. The task is challenging due to the facts that (1) training images with ground-truth labels are difficult to obtain, and (2) variations among different subordinate categories are subtle. It is well established that characterizing features of different subordinate categories are located on local parts of object instances. In fact, careful part annotations are available in many fine-grained categorization datasets. However, manually annotating object parts requires expertise, which is also difficult to generalize to new fine-grained categorization tasks. In this work, we propose a Weakly Supervised Part Detection Network (PartNet) that is able to detect discriminative local parts for use of fine-grained categorization. A vanilla PartNet builds on top of a base subnetwork two parallel streams of upper network layers, which respectively compute scores of classification probabilities (over subordinate categories) and detection probabilities (over a specified number of discriminative part detectors) for local regions of interest (RoIs). The image-level prediction is obtained by aggregating element-wise products of these region-level probabilities. To generate a diverse set of RoIs as inputs of PartNet, we propose a simple Discretized Part Proposals module (DPP) that directly targets for proposing candidates of discriminative local parts, with no bridging via object-level proposals. Experiments on the benchmark CUB-200-2011 and Oxford Flower 102 datasets show the efficacy of our proposed method for both discriminative part detection and fine-grained categorization. In particular, we achieve the new state-of-the-art performance on CUB-200-2011 dataset when ground-truth part annotations are not available.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1806.06198](https://arxiv.org/abs/1806.06198)

##### PDF
[https://arxiv.org/pdf/1806.06198](https://arxiv.org/pdf/1806.06198)

