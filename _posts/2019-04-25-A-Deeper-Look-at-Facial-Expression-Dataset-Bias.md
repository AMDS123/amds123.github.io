---
layout: post
title: "A Deeper Look at Facial Expression Dataset Bias"
date: 2019-04-25 04:07:13
categories: arXiv_CV
tags: arXiv_CV Quantitative Recognition
author: Shan Li, Weihong Deng
mathjax: true
---

* content
{:toc}

##### Abstract
Datasets play an important role in the progress of facial expression recognition algorithms, but they may suffer from obvious biases caused by different cultures and collection conditions. To look deeper into this bias, we first conduct comprehensive experiments on dataset recognition and crossdataset generalization tasks, and for the first time explore the intrinsic causes of the dataset discrepancy. The results quantitatively verify that current datasets have a strong buildin bias and corresponding analyses indicate that the conditional probability distributions between source and target datasets are different. However, previous researches are mainly based on shallow features with limited discriminative ability under the assumption that the conditional distribution remains unchanged across domains. To address these issues, we further propose a novel deep Emotion-Conditional Adaption Network (ECAN) to learn domain-invariant and discriminative feature representations, which can match both the marginal and the conditional distributions across domains simultaneously. In addition, the largely ignored expression class distribution bias is also addressed by a learnable re-weighting parameter, so that the training and testing domains can share similar class distribution. Extensive cross-database experiments on both lab-controlled datasets (CK+, JAFFE, MMI and Oulu-CASIA) and real-world databases (AffectNet, FER2013, RAF-DB 2.0 and SFEW 2.0) demonstrate that our ECAN can yield competitive performances across various facial expression transfer tasks and outperform the state-of-theart methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.11150](http://arxiv.org/abs/1904.11150)

##### PDF
[http://arxiv.org/pdf/1904.11150](http://arxiv.org/pdf/1904.11150)

