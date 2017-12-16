---
layout: post
title: "Optimizing and Visualizing Deep Learning for Benign/Malignant Classification in Breast Tumors"
date: 2017-05-17 22:35:28
categories: arXiv_CV
tags: arXiv_CV CNN Classification Deep_Learning Prediction
author: Darvin Yi, Rebecca Lynn Sawyer, David Cohn III, Jared Dunnmon, Carson Lam, Xuerong Xiao, Daniel Rubin
mathjax: true
---

* content
{:toc}

##### Abstract
Breast cancer has the highest incidence and second highest mortality rate for women in the US. Our study aims to utilize deep learning for benign/malignant classification of mammogram tumors using a subset of cases from the Digital Database of Screening Mammography (DDSM). Though it was a small dataset from the view of Deep Learning (about 1000 patients), we show that currently state of the art architectures of deep learning can find a robust signal, even when trained from scratch. Using convolutional neural networks (CNNs), we are able to achieve an accuracy of 85% and an ROC AUC of 0.91, while leading hand-crafted feature based methods are only able to achieve an accuracy of 71%. We investigate an amalgamation of architectures to show that our best result is reached with an ensemble of the lightweight GoogLe Nets tasked with interpreting both the coronal caudal view and the mediolateral oblique view, simply averaging the probability scores of both views to make the final prediction. In addition, we have created a novel method to visualize what features the neural network detects for the benign/malignant classification, and have correlated those features with well known radiological features, such as spiculation. Our algorithm significantly improves existing classification methods for mammography lesions and identifies features that correlate with established clinical markers.

##### Abstract (translated by Google)
在美国，乳腺癌发病率最高，死亡率居第二位。我们的研究旨在利用乳腺X线摄影数字数据库（DDSM）的一个病例子集，利用深度学习对乳房X线照片肿瘤进行良性/恶性分类。尽管从深度学习（大约1000名患者）的角度来看，这是一个很小的数据集，但是我们表明，目前最先进的深度学习体系结构可以找到一个强大的信号，即使是从零开始训练。使用卷积神经网络（CNNs），我们能够达到85％的准确度和0.91的ROC AUC，而领先的手工特征方法仅能够达到71％的准确度。我们调查的架构的融合，以显示我们的最好成绩达到与解释都冠状尾视图和内外侧斜视图，简单平均两种观点的概率得分，使最终的预测责成轻量级谷歌网队的合奏。此外，我们创建了一种新方法，可视化神经网络检测良性/恶性分类的特征，并将这些特征与众所周知的放射性特征（如针刺）相关联。我们的算法显着改善乳房X线照相病变的现有分类方法，并确定与已建立的临床标记相关的特征。

##### URL
[https://arxiv.org/abs/1705.06362](https://arxiv.org/abs/1705.06362)

##### PDF
[https://arxiv.org/pdf/1705.06362](https://arxiv.org/pdf/1705.06362)

