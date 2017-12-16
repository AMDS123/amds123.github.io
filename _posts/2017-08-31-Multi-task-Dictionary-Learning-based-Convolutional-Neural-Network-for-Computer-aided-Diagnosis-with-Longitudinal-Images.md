---
layout: post
title: "Multi-task Dictionary Learning based Convolutional Neural Network for Computer aided Diagnosis with Longitudinal Images"
date: 2017-08-31 18:58:59
categories: arXiv_CV
tags: arXiv_CV Sparse Knowledge CNN Image_Classification Transfer_Learning Classification Deep_Learning
author: Jie Zhang, Qingyang Li, Richard J. Caselli, Jieping Ye, Yalin Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Algorithmic image-based diagnosis and prognosis of neurodegenerative diseases on longitudinal data has drawn great interest from computer vision researchers. The current state-of-the-art models for many image classification tasks are based on the Convolutional Neural Networks (CNN). However, a key challenge in applying CNN to biological problems is that the available labeled training samples are very limited. Another issue for CNN to be applied in computer aided diagnosis applications is that to achieve better diagnosis and prognosis accuracy, one usually has to deal with the longitudinal dataset, i.e., the dataset of images scanned at different time points. Here we argue that an enhanced CNN model with transfer learning for the joint analysis of tasks from multiple time points or regions of interests may have a potential to improve the accuracy of computer aided diagnosis. To reach this goal, we innovate a CNN based deep learning multi-task dictionary learning framework to address the above challenges. Firstly, we pre-train CNN on the ImageNet dataset and transfer the knowledge from the pre-trained model to the medical imaging progression representation, generating the features for different tasks. Then, we propose a novel unsupervised learning method, termed Multi-task Stochastic Coordinate Coding (MSCC), for learning different tasks by using shared and individual dictionaries and generating the sparse features required to predict the future cognitive clinical scores. We apply our new model in a publicly available neuroimaging cohort to predict clinical measures with two different feature sets and compare them with seven other state-of-the-art methods. The experimental results show our proposed method achieved superior results.

##### Abstract (translated by Google)
基于图像的纵向数据对神经退行性疾病的诊断和预后已引起计算机视觉研究者的极大兴趣。目前用于许多图像分类任务的最新模型是基于卷积神经网络（CNN）。然而，将CNN用于生物问题的一个关键挑战是现有的标记培训样本非常有限。将CNN应用于计算机辅助诊断应用的另一个问题是，为了获得更好的诊断和预后准确性，通常需要处理纵向数据集，即在不同时间点扫描的图像的数据集。在这里，我们认为，一个增强CNN模型与转移学习的联合分析任务从多个时间点或感兴趣的地区可能有可能提高计算机辅助诊断的准确性。为了实现这一目标，我们创新了基于CNN的深度学习多任务词典学习框架，以应对上述挑战。首先，我们在ImageNet数据集上预先训练CNN，将知识从预先训练的模型转移到医学成像进展表示中，为不同的任务生成特征。然后，我们提出了一种新的无监督学习方法，称为多任务随机坐标编码（MSCC），通过使用共享和个人词典学习不同的任务，并产生预测未来认知临床评分所需的稀疏特征。我们应用我们的新模型在一个公开的神经影像学队列中预测临床措施与两个不同的功能集，并与七个其他最先进的方法进行比较。实验结果表明，我们提出的方法取得了较好的结果

##### URL
[https://arxiv.org/abs/1709.00042](https://arxiv.org/abs/1709.00042)

##### PDF
[https://arxiv.org/pdf/1709.00042](https://arxiv.org/pdf/1709.00042)

