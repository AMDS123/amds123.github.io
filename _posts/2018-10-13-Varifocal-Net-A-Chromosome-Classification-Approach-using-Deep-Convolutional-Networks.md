---
layout: post
title: "Varifocal-Net: A Chromosome Classification Approach using Deep Convolutional Networks"
date: 2018-10-13 23:39:39
categories: arXiv_CV
tags: arXiv_CV CNN Classification Detection
author: Yulei Qin, Ning Song, Hao Zheng, Xiaolin Huang, Jie Yang, Yue-Min Zhu, Guang-Zhong Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Chromosome classification is critical for karyotyping in abnormality diagnosis. To relieve doctors from such tedious work and expedite abnormality diagnosis, we present a novel method named Varifocal-Net for simultaneous classification of chromosome's type and polarity using deep convolutional networks. The approach consists of one global-scale network (G-Net) and one local-scale network (L-Net). It follows two stages. The first stage is to learn both global and local features. We extract global features and detect finer local regions via the G-Net. With the proposed varifocal mechanism, we zoom into local parts and extract local features via the L-Net. Residual learning and multi-task learning strategy are utilized to promote high-level feature extraction. The detection of discriminative local parts is fulfilled by a localization subnet in the G-Net, whose training process involves both supervised and weakly-supervised learning. The second stage is to build two multi-layer perceptron classifiers that exploit features of both two scales to boost classification performance. We constructed a large dataset with 1909 karyotyping cases for extensive experiments. Evaluation results demonstrate that our Varifocal-Net achieved the highest accuracy of 0.9805, 0.9909 and average F1-score of 0.9771, 0.9909 for the type and polarity task, respectively. It outperformed state-of-the-art methods, which proves the effectiveness of our varifocal mechanism and multi-scale feature ensemble. The Varifocal-Net has been applied into clinical practice of karyotyping to assist numerical abnormality diagnosis.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.05943](https://arxiv.org/abs/1810.05943)

##### PDF
[https://arxiv.org/pdf/1810.05943](https://arxiv.org/pdf/1810.05943)

