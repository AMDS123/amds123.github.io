---
layout: post
title: "Born Again Neural Networks"
date: 2018-05-12 19:48:50
categories: arXiv_AI
tags: arXiv_AI Knowledge Language_Model Prediction
author: Tommaso Furlanello, Zachary C. Lipton, Michael Tschannen, Laurent Itti, Anima Anandkumar
mathjax: true
---

* content
{:toc}

##### Abstract
Knowledge distillation (KD) consists of transferring knowledge from one machine learning model (the teacher}) to another (the student). Commonly, the teacher is a high-capacity model with formidable performance, while the student is more compact. By transferring knowledge, one hopes to benefit from the student's compactness. %we desire a compact model with performance close to the teacher's. We study KD from a new perspective: rather than compressing models, we train students parameterized identically to their teachers. Surprisingly, these {Born-Again Networks (BANs), outperform their teachers significantly, both on computer vision and language modeling tasks. Our experiments with BANs based on DenseNets demonstrate state-of-the-art performance on the CIFAR-10 (3.5%) and CIFAR-100 (15.5%) datasets, by validation error. Additional experiments explore two distillation objectives: (i) Confidence-Weighted by Teacher Max (CWTM) and (ii) Dark Knowledge with Permuted Predictions (DKPP). Both methods elucidate the essential components of KD, demonstrating a role of the teacher outputs on both predicted and non-predicted classes. We present experiments with students of various capacities, focusing on the under-explored case where students overpower teachers. Our experiments show significant advantages from transferring knowledge between DenseNets and ResNets in either direction.

##### Abstract (translated by Google)
知识蒸馏（KD）包括将知识从一个机器学习模型（教师}）转移到另一个（学生）。一般来说，老师是一个具有强大表现的高容量模型，而学生更紧凑。通过传授知识，人们希望从学生的紧凑中受益。我们希望有一款紧凑型的紧凑型教练机。我们从一个新的角度研究KD：我们不是对模型进行压缩，而是将学生的参数化训练与他们的老师相同。令人惊讶的是，这些{Born-Again Networks（BANs）在计算机视觉和语言建模任务方面都优于老师。我们对基于DenseNets的BAN进行的实验通过验证错误证明了CIFAR-10（3.5％）和CIFAR-100（15.5％）数据集的最新性能。其他实验探索两个蒸馏目标：（i）教师最大值（CWTM）的置信加权和（ii）带置换预测的黑暗知识（DKPP）。两种方法都阐明了KD的基本组成部分，证明了教师输出对预测和非预测类别的作用。我们向不同能力的学生展示实验，重点讨论学生压倒教师的未被发现的案例。我们的实验显示了在任何方向上在DenseNets和ResNets之间传递知识方面的显着优势。

##### URL
[https://arxiv.org/abs/1805.04770](https://arxiv.org/abs/1805.04770)

##### PDF
[https://arxiv.org/pdf/1805.04770](https://arxiv.org/pdf/1805.04770)

