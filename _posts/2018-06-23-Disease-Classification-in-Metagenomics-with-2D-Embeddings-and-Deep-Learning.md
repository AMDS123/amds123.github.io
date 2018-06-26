---
layout: post
title: "Disease Classification in Metagenomics with 2D Embeddings and Deep Learning"
date: 2018-06-23 22:01:27
categories: arXiv_CV
tags: arXiv_CV Embedding CNN Classification Deep_Learning
author: Thanh Hai Nguyen, Edi Prifti, Yann Chevaleyre, Nataliya Sokolovska, Jean-Daniel Zucker
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning (DL) techniques have shown unprecedented success when applied to images, waveforms, and text. Generally, when the sample size ($N$) is much bigger than the number of features ($d$), DL often outperforms other machine learning (ML) techniques, often through the use of Convolutional Neural Networks (CNNs). However, in many bioinformatics fields (including metagenomics), we encounter the opposite situation where $d$ is significantly greater than $N$. In these situations, applying DL techniques would lead to severe overfitting. 
 Here we aim to improve classification of various diseases with metagenomic data through the use of CNNs. For this we proposed to represent metagenomic data as images. The proposed Met2Img approach relies on taxonomic and t-SNE embeddings to transform abundance data into "synthetic images". 
 We applied our approach to twelve benchmark data sets including more than 1400 metagenomic samples. Our results show significant improvements over the state-of-the-art algorithms (Random Forest (RF), Support Vector Machine (SVM)). We observe that the integration of phylogenetic information alongside abundance data improves classification. The proposed approach is not only important in classification setting but also allows to visualize complex metagenomic data. The Met2Img is implemented in Python.

##### Abstract (translated by Google)
深度学习（DL）技术在应用于图像，波形和文本时表现出前所未有的成功。通常，当样本大小（$ N $）比特征数量（$ d $）大得多时，通常通过使用卷积神经网络（CNN），DL往往胜过其他机器学习（ML）技术。然而，在许多生物信息学领域（包括宏基因组学）中，我们遇到相反的情况，其中$ d $显着大于$ N $。在这些情况下，应用DL技术会导致严重的过度配合。
 这里我们的目标是通过使用CNN来改善使用宏基因组数据对各种疾病的分类。为此，我们提出将宏基因组数据表示为图像。提出的Met2Img方法依赖于分类学和t-SNE嵌入来将丰度数据转换成“合成图像”。
 我们将我们的方法应用于12个基准数据集，其中包括1400多个宏基因组样本。我们的结果显示了对最先进的算法（随机森林（RF），支持向量机（SVM））的显着改进。我们观察到系统发育信息与丰度数据的整合提高了分类。所提出的方法不仅在分类设置中很重要，而且还可以使复杂的宏基因组数据可视化。 Met2Img是用Python实现的。

##### URL
[http://arxiv.org/abs/1806.09046](http://arxiv.org/abs/1806.09046)

##### PDF
[http://arxiv.org/pdf/1806.09046](http://arxiv.org/pdf/1806.09046)

