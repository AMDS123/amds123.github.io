---
layout: post
title: "L2AE-D: Learning to Aggregate Embeddings for Few-shot Learning with Meta-level Dropout"
date: 2019-04-08 20:11:39
categories: arXiv_CV
tags: arXiv_CV Attention Embedding CNN Classification Recognition
author: Heda Song, Mercedes Torres Torres, Ender &#xd6;zcan, Isaac Triguero
mathjax: true
---

* content
{:toc}

##### Abstract
Few-shot learning focuses on learning a new visual concept with very limited labelled examples. A successful approach to tackle this problem is to compare the similarity between examples in a learned metric space based on convolutional neural networks. However, existing methods typically suffer from meta-level overfitting due to the limited amount of training tasks and do not normally consider the importance of the convolutional features of different examples within the same channel. To address these limitations, we make the following two contributions: (a) We propose a novel meta-learning approach for aggregating useful convolutional features and suppressing noisy ones based on a channel-wise attention mechanism to improve class representations. The proposed model does not require fine-tuning and can be trained in an end-to-end manner. The main novelty lies in incorporating a shared weight generation module that learns to assign different weights to the feature maps of different examples within the same channel. (b) We also introduce a simple meta-level dropout technique that reduces meta-level overfitting in several few-shot learning approaches. In our experiments, we find that this simple technique significantly improves the performance of the proposed method as well as various state-of-the-art meta-learning algorithms. Applying our method to few-shot image recognition using Omniglot and miniImageNet datasets shows that it is capable of delivering a state-of-the-art classification performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.04339](http://arxiv.org/abs/1904.04339)

##### PDF
[http://arxiv.org/pdf/1904.04339](http://arxiv.org/pdf/1904.04339)

