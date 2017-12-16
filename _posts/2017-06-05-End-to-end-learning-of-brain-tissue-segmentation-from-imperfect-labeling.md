---
layout: post
title: "End-to-end learning of brain tissue segmentation from imperfect labeling"
date: 2017-06-05 20:14:37
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Inference Deep_Learning
author: Alex Fedorov, Jeremy Johnson, Eswar Damaraju, Alexei Ozerin, Vince Calhoun, Sergey Plis
mathjax: true
---

* content
{:toc}

##### Abstract
Segmenting a structural magnetic resonance imaging (MRI) scan is an important pre-processing step for analytic procedures and subsequent inferences about longitudinal tissue changes. Manual segmentation defines the current gold standard in quality but is prohibitively expensive. Automatic approaches are computationally intensive, incredibly slow at scale, and error prone due to usually involving many potentially faulty intermediate steps. In order to streamline the segmentation, we introduce a deep learning model that is based on volumetric dilated convolutions, subsequently reducing both processing time and errors. Compared to its competitors, the model has a reduced set of parameters and thus is easier to train and much faster to execute. The contrast in performance between the dilated network and its competitors becomes obvious when both are tested on a large dataset of unprocessed human brain volumes. The dilated network consistently outperforms not only another state-of-the-art deep learning approach, the up convolutional network, but also the ground truth on which it was trained. Not only can the incredible speed of our model make large scale analyses much easier but we also believe it has great potential in a clinical setting where, with little to no substantial delay, a patient and provider can go over test results.

##### Abstract (translated by Google)
分割结构磁共振成像（MRI）扫描是分析程序和关于纵向组织变化的后续推断的重要预处理步骤。手动分割定义了当前质量的黄金标准，但是过于昂贵。自动方法计算密集，规模难以置信，并且由于通常涉及许多潜在的错误中间步骤而容易出错。为了简化分割，我们引入了基于体积扩张卷积的深度学习模型，随后减少了处理时间和错误。与其竞争对手相比，该模型具有减少的参数集，因此更容易培训，执行速度更快。扩张的网络和竞争对手之间的性能对比在两个测试数据集都是未经处理的人脑容量的情况下变得明显。扩张的网络不仅比另一个最先进的深度学习方法，上卷积网络，还有它被训练的实际情况都要好。我们的模型的不可思议的速度不仅可以使大规模分析变得更容易，而且我们也相信它在临床环境中具有巨大的潜力，在几乎没有实质性延迟的情况下，患者和提供者可以检查结果。

##### URL
[https://arxiv.org/abs/1612.00940](https://arxiv.org/abs/1612.00940)

##### PDF
[https://arxiv.org/pdf/1612.00940](https://arxiv.org/pdf/1612.00940)

