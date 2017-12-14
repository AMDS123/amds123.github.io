---
layout: post
title: "Zero-Shot Learning via Category-Specific Visual-Semantic Mapping"
date: 2017-12-13 03:46:07
categories: arXiv_CV
tags: arXiv_CV Embedding Image_Classification Classification
author: Li Niu, Jianfei Cai, Ashok Veeraraghavan
mathjax: true
---

* content
{:toc}

##### Abstract
Zero-Shot Learning (ZSL) aims to classify a test instance from an unseen category based on the training instances from seen categories, in which the gap between seen categories and unseen categories is generally bridged via visual-semantic mapping between the low-level visual feature space and the intermediate semantic space. However, the visual-semantic mapping learnt based on seen categories may not generalize well to unseen categories because the data distributions between seen categories and unseen categories are considerably different, which is known as the projection domain shift problem in ZSL. To address this domain shift issue, we propose a method named Adaptive Embedding ZSL (AEZSL) to learn an adaptive visual-semantic mapping for each unseen category based on the similarities between each unseen category and all the seen categories. Then, we further make two extensions based on our AEZSL method. Firstly, in order to utilize the unlabeled test instances from unseen categories, we extend our AEZSL to a semi-supervised approach named AEZSL with Label Refinement (AEZSL_LR), in which a progressive approach is developed to update the visual classifiers and refine the predicted test labels alternatively based on the similarities among test instances and among unseen categories. Secondly, to avoid learning visual-semantic mapping for each unseen category in the large-scale classification task, we extend our AEZSL to a deep adaptive embedding model named Deep AEZSL (DAEZSL) sharing the similar idea (i.e., visual-semantic mapping should be category-specific and related to the semantic space) with AEZSL, which only needs to be trained once, but can be applied to arbitrary number of unseen categories. Extensive experiments demonstrate that our proposed methods achieve the state-of-the-art results for image classification on four benchmark datasets.

##### Abstract (translated by Google)
零点学习（Zero-Shot Learning，ZSL）旨在根据所看到的类别中的训练实例，对一个看不见的类别中的测试实例进行分类，其中所看到的类别和看不见的类别之间的差距通常是通过低级视觉之间的视觉语义映射特征空间和中间语义空间。然而，基于所看到的类别学习的视觉语义映射对于看不见的类别可能并不能很好地推广，因为所看到的类别和看不见的类别之间的数据分布有很大不同，这在ZSL中被称为投影域转移问题。为了解决这个领域转移问题，我们提出了一种名为自适应嵌入ZSL（AEZSL）的方法，以基于每个看不见的类别与所有看到的类别之间的相似性，为每个看不见的类别学习自适应视觉语义映射。然后，我们进一步根据我们的AEZSL方法做两个扩展。首先，为了利用看不见的类别中未标记的测试实例，我们将AEZSL扩展为名为AEZSL的具有标注细化（AEZSL_LR）的半监督方法，其中渐进方法被开发用于更新视觉分类器并且改进预测测试基于测试实例之间的相似性以及不可见类别之间的交替标记。其次，为了避免在大规模分类任务中为每个看不见的类别学习视觉语义映射，我们将AEZSL扩展到一个深度自适应嵌入模型，名为Deep AEZSL（DAEZSL），即共享相似的想法（即，视觉 - 语义映射应该是类别特定的和与语义空间有关的）与AEZSL相结合，只需要训练一次，但可以应用于任意数量的看不见的类别。大量实验证明，我们提出的方法可以在四个基准数据集上获得最先进的图像分类结果。

##### URL
[http://arxiv.org/abs/1711.06167](http://arxiv.org/abs/1711.06167)

##### PDF
[http://arxiv.org/pdf/1711.06167](http://arxiv.org/pdf/1711.06167)

