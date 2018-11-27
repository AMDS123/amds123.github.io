---
layout: post
title: "Discriminative Feature Learning for Unsupervised Video Summarization"
date: 2018-11-24 08:49:06
categories: arXiv_CV
tags: arXiv_CV Regularization Attention Summarization
author: Yunjae Jung, Donghyeon Cho, Dahun Kim, Sanghyun Woo, In So Kweon
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we address the problem of unsupervised video summarization that automatically extracts key-shots from an input video. Specifically, we tackle two critical issues based on our empirical observations: (i) Ineffective feature learning due to flat distributions of output importance scores for each frame, and (ii) training difficulty when dealing with long-length video inputs. To alleviate the first problem, we propose a simple yet effective regularization loss term called variance loss. The proposed variance loss allows a network to predict output scores for each frame with high discrepancy which enables effective feature learning and significantly improves model performance. For the second problem, we design a novel two-stream network named Chunk and Stride Network (CSNet) that utilizes local (chunk) and global (stride) temporal view on the video features. Our CSNet gives better summarization results for long-length videos compared to the existing methods. In addition, we introduce an attention mechanism to handle the dynamic information in videos. We demonstrate the effectiveness of the proposed methods by conducting extensive ablation studies and show that our final model achieves new state-of-the-art results on two benchmark datasets.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1811.09791](https://arxiv.org/abs/1811.09791)

##### PDF
[https://arxiv.org/pdf/1811.09791](https://arxiv.org/pdf/1811.09791)

