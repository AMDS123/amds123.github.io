---
layout: post
title: "Multi-Scale Gradual Integration CNN for False Positive Reduction in Pulmonary Nodule Detection"
date: 2018-07-24 10:08:12
categories: arXiv_CV
tags: arXiv_CV GAN CNN Detection
author: Bum-Chae Kim, Jun-Sik Choi, Heung-Il Suk
mathjax: true
---

* content
{:toc}

##### Abstract
Lung cancer is a global and dangerous disease, and its early detection is crucial to reducing the risks of mortality. In this regard, it has been of great interest in developing a computer-aided system for pulmonary nodules detection as early as possible on thoracic CT scans. In general, a nodule detection system involves two steps: (i) candidate nodule detection at a high sensitivity, which captures many false positives and (ii) false positive reduction from candidates. However, due to the high variation of nodule morphological characteristics and the possibility of mistaking them for neighboring organs, candidate nodule detection remains a challenge. In this study, we propose a novel Multi-scale Gradual Integration Convolutional Neural Network (MGI-CNN), designed with three main strategies: (1) to use multi-scale inputs with different levels of contextual information, (2) to use abstract information inherent in different input scales with gradual integration, and (3) to learn multi-stream feature integration in an end-to-end manner. To verify the efficacy of the proposed network, we conducted exhaustive experiments on the LUNA16 challenge datasets by comparing the performance of the proposed method with state-of-the-art methods in the literature. On two candidate subsets of the LUNA16 dataset, i.e., V1 and V2, our method achieved an average CPM of 0.908 (V1) and 0.942 (V2), outperforming comparable methods by a large margin. Our MGI-CNN is implemented in Python using TensorFlow and the source code is available from 'https://github.com/ku-milab/MGICNN.'

##### Abstract (translated by Google)
肺癌是一种全球性和危险的疾病，其早期发现对降低死亡风险至关重要。在这方面，在胸部CT扫描中尽早开发用于肺结节检测的计算机辅助系统具有重要意义。通常，结节检测系统包括两个步骤：（i）高灵敏度的候选结节检测，其捕获许多假阳性和（ii）候选者的假阳性减少。然而，由于结节形态特征的高度变化以及将它们误认为邻近器官的可能性，候选结节检测仍然是一个挑战。在这项研究中，我们提出了一种新的多尺度渐进整合卷积神经网络（MGI-CNN），设计有三个主要策略：（1）使用具有不同层次的上下文信息的多尺度输入，（2）使用抽象通过逐步集成在不同输入规模中固有的信息，以及（3）以端到端方式学习多流特征集成。为了验证所提出的网络的功效，我们通过比较所提出的方法的性能与文献中的最新方法，对LUNA16挑战数据集进行了详尽的实验。在LUNA16数据集的两个候选子集上，即V1和V2，我们的方法实现了0.908（V1）和0.942（V2）的平均CPM，大大超过了可比较的方法。我们的MGI-CNN使用TensorFlow在Python中实现，源代码可从“https://github.com/ku-milab/MGICNN”获得。

##### URL
[http://arxiv.org/abs/1807.10581](http://arxiv.org/abs/1807.10581)

##### PDF
[http://arxiv.org/pdf/1807.10581](http://arxiv.org/pdf/1807.10581)

