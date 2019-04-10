---
layout: post
title: "Attention-based Multi-instance Neural Network for Medical Diagnosis from Incomplete and Low Quality Data"
date: 2019-04-09 04:21:52
categories: arXiv_CL
tags: arXiv_CL Attention Embedding Classification Relation
author: Zeyuan Wang, Josiah Poon, Shiding Sun, Simon Poon
mathjax: true
---

* content
{:toc}

##### Abstract
One way to extract patterns from clinical records is to consider each patient record as a bag with various number of instances in the form of symptoms. Medical diagnosis is to discover informative ones first and then map them to one or more diseases. In many cases, patients are represented as vectors in some feature space and a classifier is applied after to generate diagnosis results. However, in many real-world cases, data is often of low-quality due to a variety of reasons, such as data consistency, integrity, completeness, accuracy, etc. In this paper, we propose a novel approach, attention based multi-instance neural network (AMI-Net), to make the single disease classification only based on the existing and valid information in the real-world outpatient records. In the context of a patient, it takes a bag of instances as input and output the bag label directly in end-to-end way. Embedding layer is adopted at the beginning, mapping instances into an embedding space which represents the individual patient condition. The correlations among instances and their importance for the final classification are captured by multi-head attention transformer, instance-level multi-instance pooling and bag-level multi-instance pooling. The proposed approach was test on two non-standardized and highly imbalanced datasets, one in the Traditional Chinese Medicine (TCM) domain and the other in the Western Medicine (WM) domain. Our preliminary results show that the proposed approach outperforms all baselines results by a significant margin.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.04460](http://arxiv.org/abs/1904.04460)

##### PDF
[http://arxiv.org/pdf/1904.04460](http://arxiv.org/pdf/1904.04460)

