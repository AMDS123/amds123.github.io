---
layout: post
title: "Deep Metric Transfer for Label Propagation with Limited Annotated Data"
date: 2018-12-20 18:57:28
categories: arXiv_AI
tags: arXiv_AI Transfer_Learning Recognition
author: Bin Liu, Zhirong Wu, Han Hu, Stephen Lin
mathjax: true
---

* content
{:toc}

##### Abstract
We study object recognition under the constraint that each object class is only represented by very few observations. In such cases, naive supervised learning would lead to severe over-fitting in deep neural networks due to limited training data. We tackle this problem by creating much more training data through label propagation from the few labeled examples to a vast collection of unannotated images. Our main insight is that such a label propagation scheme can be highly effective when the similarity metric used for propagation is learned and transferred from other related domains with lots of data. We test our approach on semi-supervised learning, transfer learning and few-shot recognition, where we learn our similarity metric using various supervised/unsupervised pretraining methods, and transfer it to unlabeled data across different data distributions. By taking advantage of unlabeled data in this way, we achieve significant improvements on all three tasks. Notably, our approach outperforms current state-of-the-art techniques by an absolute $20\%$ for semi-supervised learning on CIFAR10, $10\%$ for transfer learning from ImageNet to CIFAR10, and $6\%$ for few-shot recognition on mini-ImageNet, when labeled examples are limited.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1812.08781](https://arxiv.org/abs/1812.08781)

##### PDF
[https://arxiv.org/pdf/1812.08781](https://arxiv.org/pdf/1812.08781)

