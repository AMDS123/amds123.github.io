---
layout: post
title: "BERT-Based Multi-Head Selection for Joint Entity-Relation Extraction"
date: 2019-08-16 09:29:43
categories: arXiv_CL
tags: arXiv_CL Relation_Extraction Embedding Relation Recognition
author: Weipeng Huang, Xingyi Cheng, Taifeng Wang, Wei Chu
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we report our method for the Information Extraction task in 2019 Language and Intelligence Challenge. We incorporate BERT into the multi-head selection framework for joint entity-relation extraction. This model extends existing approaches from three perspectives. First, BERT is adopted as a feature extraction layer at the bottom of the multi-head selection framework. We further optimize BERT by introducing a semantic-enhanced task during BERT pre-training. Second, we introduce a large-scale Baidu Baike corpus for entity recognition pre-training, which is of weekly supervised learning since there is no actual named entity label. Third, soft label embedding is proposed to effectively transmit information between entity recognition and relation extraction. Combining these three contributions, we enhance the information extracting ability of the multi-head selection model and achieve F1-score 0.876 on testset-1 with a single model. By ensembling four variants of our model, we finally achieve F1 score 0.892 (1st place) on testset-1 and F1 score 0.8924 (2nd place) on testset-2.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.05908](https://arxiv.org/abs/1908.05908)

##### PDF
[https://arxiv.org/pdf/1908.05908](https://arxiv.org/pdf/1908.05908)

