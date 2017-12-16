---
layout: post
title: "Optimal Transport for Deep Joint Transfer Learning"
date: 2017-09-09 18:56:05
categories: arXiv_CV
tags: arXiv_CV Knowledge Image_Classification Transfer_Learning Classification Prediction
author: Ying Lu, Liming Chen, Alexandre Saidi
mathjax: true
---

* content
{:toc}

##### Abstract
Training a Deep Neural Network (DNN) from scratch requires a large amount of labeled data. For a classification task where only small amount of training data is available, a common solution is to perform fine-tuning on a DNN which is pre-trained with related source data. This consecutive training process is time consuming and does not consider explicitly the relatedness between different source and target tasks. In this paper, we propose a novel method to jointly fine-tune a Deep Neural Network with source data and target data. By adding an Optimal Transport loss (OT loss) between source and target classifier predictions as a constraint on the source classifier, the proposed Joint Transfer Learning Network (JTLN) can effectively learn useful knowledge for target classification from source data. Furthermore, by using different kind of metric as cost matrix for the OT loss, JTLN can incorporate different prior knowledge about the relatedness between target categories and source categories. We carried out experiments with JTLN based on Alexnet on image classification datasets and the results verify the effectiveness of the proposed JTLN in comparison with standard consecutive fine-tuning. This Joint Transfer Learning with OT loss is general and can also be applied to other kind of Neural Networks.

##### Abstract (translated by Google)
从头开始训练深度神经网络（DNN）需要大量的标记数据。对于只有少量训练数据可用的分类任务，常见的解决方案是对用相关源数据预训练的DNN进行微调。这个连续的训练过程非常耗时，并没有明确考虑不同的源和目标任务之间的相关性。在本文中，我们提出了一种联合微调深度神经网络与源数据和目标数据的新方法。通过在源分类器预测和目标分类器预测之间增加最优传输损耗（OT loss）作为源分类器的约束条件，所提出的联合转移学习网络（JTLN）能够有效地从源数据中学习用于目标分类的有用知识。此外，通过使用不同类型的度量作为OT损失的成本矩阵，JTLN可以包含关于目标类别与源类别之间的相关性的不同先验知识。在Alexnet图像分类数据集上进行了基于Alexnet的JTLN实验，验证了所提出的JTLN与标准连续微调的有效性。这种OT损失的联合转移学习是一般的，也可以应用于其他种类的神经网络。

##### URL
[https://arxiv.org/abs/1709.02995](https://arxiv.org/abs/1709.02995)

##### PDF
[https://arxiv.org/pdf/1709.02995](https://arxiv.org/pdf/1709.02995)

