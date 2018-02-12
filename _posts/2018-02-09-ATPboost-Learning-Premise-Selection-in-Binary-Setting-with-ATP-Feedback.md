---
layout: post
title: "ATPboost: Learning Premise Selection in Binary Setting with ATP Feedback"
date: 2018-02-09 18:29:26
categories: arXiv_AI
tags: arXiv_AI Classification
author: Bartosz Piotrowski, Josef Urban
mathjax: true
---

* content
{:toc}

##### Abstract
ATPboost is a system for solving sets of large-theory problems by interleaving ATP runs with state-of-the-art machine learning of premise selection from the proofs. Unlike many previous approaches that use multi-label setting, the learning is implemented as binary classification that estimates the pairwise-relevance of (theorem, premise) pairs. ATPboost uses for this the XGBoost gradient boosting algorithm, which is fast and has state-of-the-art performance on many tasks. Learning in the binary setting however requires negative examples, which is nontrivial due to many alternative proofs. We discuss and implement several solutions in the context of the ATP/ML feedback loop, and show that ATPboost with such methods significantly outperforms the k-nearest neighbors multilabel classifier.

##### Abstract (translated by Google)
ATPboost是一个系统，用于通过将ATP运行与来自证明的前提选择的最先进机器学习交织来解决大量理论问题。与以前许多使用多标签设置的方法不同，学习被实现为二元分类，用于估计（定理，前提）对的成对相关性。 ATPboost使用XGBoost梯度提升算法，该算法速度快，在许多任务上都具有最先进的性能。但是，在二进制设置中学习需要负面的例子，由于许多其他的证明，这是不平凡的。我们在ATP / ML反馈环境下讨论并实现了几个解决方案，并且证明了ATPboost的这种方法明显优于k最近邻多标签分类器。

##### URL
[http://arxiv.org/abs/1802.03375](http://arxiv.org/abs/1802.03375)

##### PDF
[http://arxiv.org/pdf/1802.03375](http://arxiv.org/pdf/1802.03375)

