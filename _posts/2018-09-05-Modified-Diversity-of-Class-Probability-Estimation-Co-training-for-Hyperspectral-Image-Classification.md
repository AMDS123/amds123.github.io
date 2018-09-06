---
layout: post
title: "Modified Diversity of Class Probability Estimation Co-training for Hyperspectral Image Classification"
date: 2018-09-05 11:12:48
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification RNN Classification
author: Yan Ju, Lingling Li, Licheng Jiao, Zhongle Ren, Biao Hou, Shuyuan Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Due to the limited amount and imbalanced classes of labeled training data, the conventional supervised learning can not ensure the discrimination of the learned feature for hyperspectral image (HSI) classification. In this paper, we propose a modified diversity of class probability estimation (MDCPE) with two deep neural networks to learn spectral-spatial feature for HSI classification. In co-training phase, recurrent neural network (RNN) and convolutional neural network (CNN) are utilized as two learners to extract features from labeled and unlabeled data. Based on the extracted features, MDCPE selects most credible samples to update initial labeled data by combining k-means clustering with the traditional diversity of class probability estimation (DCPE) co-training. In this way, MDCPE can keep new labeled data class-balanced and extract discriminative features for both the minority and majority classes. During testing process, classification results are acquired by co-decision of the two learners. Experimental results demonstrate that the proposed semi-supervised co-training method can make full use of unlabeled information to enhance generality of the learners and achieve favorable accuracies on all three widely used data sets: Salinas, Pavia University and Pavia Center.

##### Abstract (translated by Google)
由于标记训练数据的数量和不平衡类别的限制，传统的监督学习不能确保对高光谱图像（HSI）分类的学习特征的区分。在本文中，我们提出了一种改进的类概率估计多样性（MDCPE）与两个深度神经网络，以学习HSI分类的谱空间特征。在共同训练阶段，循环神经网络（RNN）和卷积神经网络（CNN）被用作两个学习者从标记和未标记数据中提取特征。基于提取的特征，MDCPE通过将k均值聚类与传统的类概率估计（DCPE）协同训练的多样性相结合来选择最可靠的样本来更新初始标记数据。通过这种方式，MDCPE可以保持新标记数据的类平衡，并为少数类和多数类提取判别特征。在测试过程中，通过两个学习者的共同决策获得分类结果。实验结果表明，所提出的半监督协同训练方法可以充分利用未标记的信息来增强学习者的普遍性，并在所有三个广泛使用的数据集上获得良好的准确性：萨利纳斯，帕维亚大学和帕维亚中心。

##### URL
[http://arxiv.org/abs/1809.01436](http://arxiv.org/abs/1809.01436)

##### PDF
[http://arxiv.org/pdf/1809.01436](http://arxiv.org/pdf/1809.01436)

