---
layout: post
title: "Learning Deep Models for Face Anti-Spoofing: Binary or Auxiliary Supervision"
date: 2018-03-29 14:33:21
categories: arXiv_CV
tags: arXiv_CV Face RNN Classification Deep_Learning Recognition Face_Recognition
author: Yaojie Liu, Amin Jourabloo, Xiaoming Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Face anti-spoofing is the crucial step to prevent face recognition systems from a security breach. Previous deep learning approaches formulate face anti-spoofing as a binary classification problem. Many of them struggle to grasp adequate spoofing cues and generalize poorly. In this paper, we argue the importance of auxiliary supervision to guide the learning toward discriminative and generalizable cues. A CNN-RNN model is learned to estimate the face depth with pixel-wise supervision, and to estimate rPPG signals with sequence-wise supervision. Then we fuse the estimated depth and rPPG to distinguish live vs. spoof faces. In addition, we introduce a new face anti-spoofing database that covers a large range of illumination, subject, and pose variations. Experimental results show that our model achieves the state-of-the-art performance on both intra-database and cross-database testing.

##### Abstract (translated by Google)
面对反欺骗是防止面部识别系统出现安全漏洞的关键步骤。以前的深度学习方法将面部反欺骗描述为二元分类问题。他们中的许多人都很难掌握足够的欺骗线索并且推广不力。在本文中，我们认为辅助监督的重要性，指导学习朝着歧视性和可普遍化的线索。学习CNN-RNN模型以逐像素监测来估计面部深度，并且通过顺序监测来估计rPPG信号。然后我们融合估计的深度和rPPG来区分现场和欺骗面孔。另外，我们推出了一款新的面部反欺骗数据库，涵盖了大量的照明，主题和姿态变化。实验结果表明，我们的模型实现了数据库内和跨数据库测试的最新性能。

##### URL
[http://arxiv.org/abs/1803.11097](http://arxiv.org/abs/1803.11097)

##### PDF
[http://arxiv.org/pdf/1803.11097](http://arxiv.org/pdf/1803.11097)

