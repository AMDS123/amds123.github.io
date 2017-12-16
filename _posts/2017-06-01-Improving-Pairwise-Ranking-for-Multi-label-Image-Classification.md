---
layout: post
title: "Improving Pairwise Ranking for Multi-label Image Classification"
date: 2017-06-01 02:35:58
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification
author: Yuncheng Li, Yale Song, Jiebo Luo
mathjax: true
---

* content
{:toc}

##### Abstract
Learning to rank has recently emerged as an attractive technique to train deep convolutional neural networks for various computer vision tasks. Pairwise ranking, in particular, has been successful in multi-label image classification, achieving state-of-the-art results on various benchmarks. However, most existing approaches use the hinge loss to train their models, which is non-smooth and thus is difficult to optimize especially with deep networks. Furthermore, they employ simple heuristics, such as top-k or thresholding, to determine which labels to include in the output from a ranked list of labels, which limits their use in the real-world setting. In this work, we propose two techniques to improve pairwise ranking based multi-label image classification: (1) we propose a novel loss function for pairwise ranking, which is smooth everywhere and thus is easier to optimize; and (2) we incorporate a label decision module into the model, estimating the optimal confidence thresholds for each visual concept. We provide theoretical analyses of our loss function in the Bayes consistency and risk minimization framework, and show its benefit over existing pairwise ranking formulations. We demonstrate the effectiveness of our approach on three large-scale datasets, VOC2007, NUS-WIDE and MS-COCO, achieving the best reported results in the literature.

##### Abstract (translated by Google)
学习排名最近已经成为培养深度卷积神经网络用于各种计算机视觉任务的有吸引​​力的技术。成对排序，特别是在多标签图像分类方面取得了成功，在各种基准测试中取得了最新的成果。然而，现有的大多数方法都是利用铰链损失来训练模型，这是非光滑的，因此难以优化，特别是在深度网络中。此外，他们使用简单的启发式算法（如top-k或thresholding）来确定将哪些标签包含在排名列表中的输出中，这会限制其在现实环境中的使用。在这项工作中，我们提出了两种技术来提高基于成对的多标签图像分类的排序：（1）我们提出了一种新颖的成对排序的损失函数，这是平滑的，因此更容易优化; （2）将标签决策模块纳入模型，估计每个视觉概念的最优置信度阈值。我们提供贝叶斯一致性和风险最小化框架下的损失函数的理论分析，并显示其在现有的成对排序公式中的好处。我们在三个大规模的数据集，VOC2007，NUS-WIDE和MS-COCO上展示了我们的方法的有效性，实现了文献中最好的报告结果。

##### URL
[https://arxiv.org/abs/1704.03135](https://arxiv.org/abs/1704.03135)

##### PDF
[https://arxiv.org/pdf/1704.03135](https://arxiv.org/pdf/1704.03135)

