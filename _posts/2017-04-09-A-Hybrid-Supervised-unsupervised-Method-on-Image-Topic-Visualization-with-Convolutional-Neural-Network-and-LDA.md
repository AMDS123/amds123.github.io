---
layout: post
title: "A Hybrid Supervised-unsupervised Method on Image Topic Visualization with Convolutional Neural Network and LDA"
date: 2017-04-09 17:42:47
categories: arXiv_CV
tags: arXiv_CV CNN Quantitative Recognition
author: Kai Zhen, Mridul Birla, David Crandall, Bingjing Zhang, Judy Qiu
mathjax: true
---

* content
{:toc}

##### Abstract
Given the progress in image recognition with recent data driven paradigms, it's still expensive to manually label a large training data to fit a convolutional neural network (CNN) model. This paper proposes a hybrid supervised-unsupervised method combining a pre-trained AlexNet with Latent Dirichlet Allocation (LDA) to extract image topics from both an unlabeled life-logging dataset and the COCO dataset. We generate the bag-of-words representations of an egocentric dataset from the softmax layer of AlexNet and use LDA to visualize the subject's living genre with duplicated images. We use a subset of COCO on 4 categories as ground truth, and define consistent rate to quantitatively analyze the performance of the method, it achieves 84% for consistent rate on average comparing to 18.75% from a raw CNN model. The method is capable of detecting false labels and multi-labels from COCO dataset. For scalability test, parallelization experiments are conducted with Harp-LDA on a Intel Knights Landing cluster: to extract 1,000 topic assignments for 241,035 COCO images, it takes 10 minutes with 60 threads.

##### Abstract (translated by Google)
鉴于最近数据驱动范例在图像识别方面取得的进展，手动标记大型训练数据以适应卷积神经网络（CNN）模型仍然是昂贵的。本文提出了一种混合有监督无监督的方法，将预先训练的AlexNet与潜在狄利克雷分配（LDA）相结合，从未标记的生命日志数据集和COCO数据集中提取图像主题。我们从AlexNet的softmax图层生成一个以自我为中心的数据集，并使用LDA通过重复的图像可视化对象的生存流派。我们用四个类别的COCO子集作为基础事实，定义一致的比率来定量分析该方法的性能，平均一致率达到84％，而CNN模型的平均值为18.75％。该方法能够检测来自COCO数据集的假标签和多标签。对于可伸缩性测试，在Intel Knights Landing集群上使用Harp-LDA进行并行化实验：为241,035个COCO图像提取1000个主题分配，60个线程需要10分钟。

##### URL
[https://arxiv.org/abs/1703.05243](https://arxiv.org/abs/1703.05243)

##### PDF
[https://arxiv.org/pdf/1703.05243](https://arxiv.org/pdf/1703.05243)

