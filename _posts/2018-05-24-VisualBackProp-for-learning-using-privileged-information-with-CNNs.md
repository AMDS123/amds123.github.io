---
layout: post
title: "VisualBackProp for learning using privileged information with CNNs"
date: 2018-05-24 01:19:52
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation Attention CNN Classification Prediction
author: Devansh Bisla, Anna Choromanska
mathjax: true
---

* content
{:toc}

##### Abstract
In many machine learning applications, from medical diagnostics to autonomous driving, the availability of prior knowledge can be used to improve the predictive performance of learning algorithms and incorporate `physical,' `domain knowledge,' or `common sense' concepts into training of machine learning systems as well as verify constraints/properties of the systems. We explore the learning using privileged information paradigm and show how to incorporate the privileged information, such as segmentation mask available along with the classification label of each example, into the training stage of convolutional neural networks. This is done by augmenting the CNN model with an architectural component that effectively focuses model's attention on the desired region of the input image during the training process and that is transparent to the network's label prediction mechanism at testing. This component effectively corresponds to the visualization strategy for identifying the parts of the input, often referred to as visualization mask, that most contribute to the prediction, yet uses this strategy in reverse to the classical setting in order to enforce the desired visualization mask instead. We verify our proposed algorithms through exhaustive experiments on benchmark ImageNet and PASCAL VOC data sets and achieve improvements in the performance of $2.4\%$ and $2.7\%$ over standard single-supervision model training. Finally, we confirm the effectiveness of our approach on skin lesion classification problem.

##### Abstract (translated by Google)
在许多机器学习应用中，从医学诊断到自动驾驶，先验知识的可用性可用于提高学习算法的预测性能，并将“物理”，“领域知识”或“常识”概念纳入机器的培训学习系统以及验证系统的约束/属性。我们探索使用特权信息范例的学习，并展示如何将特权信息（例如可用的分割掩码以及每个示例的分类标签）并入卷积神经网络的训练阶段。这是通过增加CNN模型来完成的，该模型在训练过程中有效地将模型注意力集中在输入图像的期望区域上，并且对测试时网络的标签预测机制是透明的。该组件有效地对应于用于识别输入部分（通常称为可视化掩模）的可视化策略，其最有助于预测，但是与经典设置相反地使用该策略，以便实施期望的可视化掩模。我们通过基准ImageNet和PASCAL VOC数据集的详尽实验来验证我们提出的算法，并在标准单监督模型培训中实现$ 2.4 \％$和$ 2.7 \％$的性能提升。最后，我们证实了我们的方法在皮肤病变分类问题上的有效性。

##### URL
[http://arxiv.org/abs/1805.09474](http://arxiv.org/abs/1805.09474)

##### PDF
[http://arxiv.org/pdf/1805.09474](http://arxiv.org/pdf/1805.09474)

