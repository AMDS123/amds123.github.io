---
layout: post
title: "Unsupervised Learning for Surgical Motion by Learning to Predict the Future"
date: 2018-06-08 18:47:06
categories: arXiv_CV
tags: arXiv_CV RNN Prediction
author: Robert DiPietro, Gregory D. Hager
mathjax: true
---

* content
{:toc}

##### Abstract
We show that it is possible to learn meaningful representations of surgical motion, without supervision, by learning to predict the future. An architecture that combines an RNN encoder-decoder and mixture density networks (MDNs) is developed to model the conditional distribution over future motion given past motion. We show that the learned encodings naturally cluster according to high-level activities, and we demonstrate the usefulness of these learned encodings in the context of information retrieval, where a database of surgical motion is searched for suturing activity using a motion-based query. Future prediction with MDNs is found to significantly outperform simpler baselines as well as the best previously-published result for this task, advancing state-of-the-art performance from an F1 score of 0.60 +- 0.14 to 0.77 +- 0.05.

##### Abstract (translated by Google)
我们表明，通过学习预测未来，可以在没有监督的情况下学习有意义的手术运动表示。开发了一种结合了RNN编码器 - 解码器和混合密度网络（MDN）的架构，以模拟在过去的运动中未来运动的条件分布。我们表明，学习的编码根据高级活动自然地进行聚类，并且我们证明了这些学习编码在信息检索环境中的有用性，其中使用基于动作的查询来搜索外科动作数据库的缝合活动。 MDN的未来预测显着优于更简单的基线以及此任务的最佳先前发布结果，将最新的性能从0.60 +  -  0.14的F1分数提升至0.77 +  -  0.05。

##### URL
[http://arxiv.org/abs/1806.03318](http://arxiv.org/abs/1806.03318)

##### PDF
[http://arxiv.org/pdf/1806.03318](http://arxiv.org/pdf/1806.03318)

