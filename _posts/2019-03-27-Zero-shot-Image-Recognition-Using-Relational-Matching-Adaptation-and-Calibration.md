---
layout: post
title: "Zero-shot Image Recognition Using Relational Matching, Adaptation and Calibration"
date: 2019-03-27 21:07:00
categories: arXiv_AI
tags: arXiv_AI Embedding Image_Classification Classification Relation Recognition
author: Debasmit Das, C. S. George Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Zero-shot learning (ZSL) for image classification focuses on recognizing novel categories that have no labeled data available for training. The learning is generally carried out with the help of mid-level semantic descriptors associated with each class. This semantic-descriptor space is generally shared by both seen and unseen categories. However, ZSL suffers from hubness, domain discrepancy and biased-ness towards seen classes. To tackle these problems, we propose a three-step approach to zero-shot learning. Firstly, a mapping is learned from the semantic-descriptor space to the image-feature space. This mapping learns to minimize both one-to-one and pairwise distances between semantic embeddings and the image features of the corresponding classes. Secondly, we propose test-time domain adaptation to adapt the semantic embedding of the unseen classes to the test data. This is achieved by finding correspondences between the semantic descriptors and the image features. Thirdly, we propose scaled calibration on the classification scores of the seen classes. This is necessary because the ZSL model is biased towards seen classes as the unseen classes are not used in the training. Finally, to validate the proposed three-step approach, we performed experiments on four benchmark datasets where the proposed method outperformed previous results. We also studied and analyzed the performance of each component of our proposed ZSL framework.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.11701](http://arxiv.org/abs/1903.11701)

##### PDF
[http://arxiv.org/pdf/1903.11701](http://arxiv.org/pdf/1903.11701)

