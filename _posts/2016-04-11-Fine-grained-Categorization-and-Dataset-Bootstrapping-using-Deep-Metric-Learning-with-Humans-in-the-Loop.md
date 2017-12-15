---
layout: post
title: "Fine-grained Categorization and Dataset Bootstrapping using Deep Metric Learning with Humans in the Loop"
date: 2016-04-11 04:34:13
categories: arXiv_CV
tags: arXiv_CV Embedding
author: Yin Cui, Feng Zhou, Yuanqing Lin, Serge Belongie
mathjax: true
---

* content
{:toc}

##### Abstract
Existing fine-grained visual categorization methods often suffer from three challenges: lack of training data, large number of fine-grained categories, and high intraclass vs. low inter-class variance. In this work we propose a generic iterative framework for fine-grained categorization and dataset bootstrapping that handles these three challenges. Using deep metric learning with humans in the loop, we learn a low dimensional feature embedding with anchor points on manifolds for each category. These anchor points capture intra-class variances and remain discriminative between classes. In each round, images with high confidence scores from our model are sent to humans for labeling. By comparing with exemplar images, labelers mark each candidate image as either a "true positive" or a "false positive". True positives are added into our current dataset and false positives are regarded as "hard negatives" for our metric learning model. Then the model is retrained with an expanded dataset and hard negatives for the next round. To demonstrate the effectiveness of the proposed framework, we bootstrap a fine-grained flower dataset with 620 categories from Instagram images. The proposed deep metric learning scheme is evaluated on both our dataset and the CUB-200-2001 Birds dataset. Experimental evaluations show significant performance gain using dataset bootstrapping and demonstrate state-of-the-art results achieved by the proposed deep metric learning methods.

##### Abstract (translated by Google)
现有的细粒度视觉分类方法经常面临三个挑战：缺乏训练数据，大量细粒度类别，高级别内部与低级别间差异。在这项工作中，我们提出了一个适用于细粒度分类和数据集引导的通用迭代框架，以处理这三个挑战。在循环中使用人类的深度度量学习，我们学习了每个类别的流形上的锚点的低维特征嵌入。这些锚点捕获类内差异，并保持类之间的区别。在每一轮，从我们的模型具有高置信度得分的图像被发送给人类进行标记。通过与示例图像比较，贴标者将每个候选图像标记为“真正的”或“假的正面”。我们当前的数据集中增加了真正的积极因素，误判率被认为是我们的度量学习模型的“硬性负面因素”。然后，这个模型被扩展的数据集重新训练，而下一轮则是很难的。为了证明所提出的框架的有效性，我们从Instagram图像引导了620个细分的花朵数据集。提出的深度度量学习方案在我们的数据集和CUB-200-2001鸟类数据集上进行评估。实验评估显示使用数据集自举获得显着的性能增益，并证明了所提出的深度量度学习方法达到的最新技术成果。

##### URL
[https://arxiv.org/abs/1512.05227](https://arxiv.org/abs/1512.05227)

##### PDF
[https://arxiv.org/pdf/1512.05227](https://arxiv.org/pdf/1512.05227)

