---
layout: post
title: "Question Type Guided Attention in Visual Question Answering"
date: 2018-07-18 20:43:42
categories: arXiv_CV
tags: arXiv_CV QA Attention VQA Recognition
author: Yang Shi, Tommaso Furlanello, Sheng Zha, Animashree Anandkumar
mathjax: true
---

* content
{:toc}

##### Abstract
Visual Question Answering (VQA) requires integration of feature maps with drastically different structures and focus of the correct regions. Image descriptors have structures at multiple spatial scales, while lexical inputs inherently follow a temporal sequence and naturally cluster into semantically different question types. A lot of previous works use complex models to extract feature representations but neglect to use high-level information summary such as question types in learning. In this work, we propose Question Type-guided Attention (QTA). It utilizes the information of question type to dynamically balance between bottom-up and top-down visual features, respectively extracted from ResNet and Faster R-CNN networks. We experiment with multiple VQA architectures with extensive input ablation studies over the TDIUC dataset and show that QTA systematically improves the performance by more than 5% across multiple question type categories such as "Activity Recognition", "Utility" and "Counting" on TDIUC dataset. By adding QTA on the state-of-art model MCB, we achieve 3% improvement for overall accuracy. Finally, we propose a multi-task extension to predict question types which generalizes QTA to applications that lack of question type, with minimal performance loss.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1804.02088](https://arxiv.org/abs/1804.02088)

##### PDF
[https://arxiv.org/pdf/1804.02088](https://arxiv.org/pdf/1804.02088)

