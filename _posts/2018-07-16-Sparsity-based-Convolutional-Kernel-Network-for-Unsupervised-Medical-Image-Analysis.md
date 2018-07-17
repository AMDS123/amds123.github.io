---
layout: post
title: "Sparsity-based Convolutional Kernel Network for Unsupervised Medical Image Analysis"
date: 2018-07-16 01:33:00
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Sparse CNN Classification Deep_Learning
author: Euijoon Ahn, Jinman Kim, Ashnil Kumar, Michael Fulham, Dagan Feng
mathjax: true
---

* content
{:toc}

##### Abstract
The availability of large-scale annotated image datasets coupled with recent advances in supervised deep learning methods are enabling the derivation of representative image features that can potentially impact different image analysis problems. However, such supervised approaches are not feasible in the medical domain where it is challenging to obtain a large volume of labelled data due to the complexity of manual annotation and inter- and intra-observer variability in label assignment. Algorithms designed to work on small annotated datasets are useful but have limited applications. In an effort to address the lack of annotated data in the medical image analysis domain, we propose an algorithm for hierarchical unsupervised feature learning. Our algorithm introduces three new contributions: (i) we use kernel learning to identify and represent invariant characteristics across image sub-patches in an unsupervised manner; (ii) we leverage the sparsity inherent to medical image data and propose a new sparse convolutional kernel network (S-CKN) that can be pre-trained in a layer-wise fashion, thereby providing initial discriminative features for medical data; and (iii) we propose a spatial pyramid pooling framework to capture subtle geometric differences in medical image data. Our experiments evaluate our algorithm in two common application areas of medical image retrieval and classification using two public datasets. Our results demonstrate that the medical image feature representations extracted with our algorithm enable a higher accuracy in both application areas compared to features extracted from other conventional unsupervised methods. Furthermore, our approach achieves an accuracy that is competitive with state-of-the-art supervised CNNs.

##### Abstract (translated by Google)
大规模注释图像数据集的可用性以及监督深度学习方法的最新进展使得能够推导可能潜在地影响不同图像分析问题的代表性图像特征。然而，由于手动注释的复杂性以及标签分配中的观察者间和观察者内的可变性，这种受监督的方法在医学领域中是不可行的，其中获得大量标记数据是具有挑战性的。设计用于小注释数据集的算法很有用，但应用有限。为了解决医学图像分析领域中缺少注释数据的问题，我们提出了一种用于分层无监督特征学习的算法。我们的算法引入了三个新的贡献：（i）我们使用内核学习以无监督的方式识别和表示图像子补丁中的不变特征; （ii）我们利用医学图像数据固有的稀疏性，并提出一种新的稀疏卷积核心网络（S-CKN），它可以以分层方式进行预训练，从而为医学数据提供初始判别特征; （iii）我们提出了一个空间金字塔汇集框架，以捕捉医学图像数据中微妙的几何差异。我们的实验使用两个公共数据集在医学图像检索和分类的两个常见应用领域中评估我们的算法。我们的结果表明，与从其他传统的无监督方法中提取的特征相比，使用我们的算法提取的医学图像特征表示在两个应用领域中都能够实现更高的准确度。此外，我们的方法实现了与最先进的监督CNN竞争的准确性。

##### URL
[http://arxiv.org/abs/1807.05648](http://arxiv.org/abs/1807.05648)

##### PDF
[http://arxiv.org/pdf/1807.05648](http://arxiv.org/pdf/1807.05648)

