---
layout: post
title: "Improving Landmark Localization with Semi-Supervised Learning"
date: 2017-12-06 00:04:05
categories: arXiv_CV
tags: arXiv_CV Regularization Object_Detection Face Classification Prediction Detection
author: Sina Honari, Pavlo Molchanov, Stephen Tyree, Pascal Vincent, Christopher Pal, Jan Kautz
mathjax: true
---

* content
{:toc}

##### Abstract
We present two techniques to improve landmark localization from partially annotated datasets. Our primary goal is to leverage the common situation where precise landmark locations are only provided for a small data subset, but where class labels for classification tasks related to the landmarks are more abundantly available. We propose a new architecture for landmark localization, where training with class labels acts as an auxiliary signal to guide the landmark localization on unlabeled data. A key aspect of our approach is that errors can be backpropagated through a complete landmark localization model. We also propose and explore an unsupervised learning technique for landmark localization based on having a model predict equivariant landmarks with respect to transformations applied to the image. We show that this technique, used as additional regularization, improves landmark prediction considerably and can learn effective detectors even when only a small fraction of the dataset has labels for landmarks. We present results on two toy datasets and three real datasets, with hands and faces, respectively, showing the performance gain of our method on each.

##### Abstract (translated by Google)
我们提出了两种技术来提高从部分注释的数据集的地标本地化。我们的主要目标是利用常见的情况，即精确的地标位置仅为小数据子集提供，但与地标有关的分类任务的类别标签更为丰富。我们提出了一个新的地标本地化体系结构，其中类标签训练作为一个辅助信号来指导未标记数据的地标本地化。我们的方法的一个关键方面是可以通过一个完整的地标本地化模型反向传播错误。我们还提出和探索一种基于模型预测等效地标与应用于图像转换的地标定位的无监督学习技术。我们表明，这种技术，作为额外的正则化，大大改善了地标预测，并可以学习有效的探测器，即使只有一小部分的数据集标签的地标。我们在两个玩具数据集和三个真实数据集上分别显示了结果，用手和面分别显示了我们的方法在每个数据集上的性能增益。

##### URL
[http://arxiv.org/abs/1709.01591](http://arxiv.org/abs/1709.01591)

##### PDF
[http://arxiv.org/pdf/1709.01591](http://arxiv.org/pdf/1709.01591)

