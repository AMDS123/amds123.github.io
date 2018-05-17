---
layout: post
title: "Image Classification Based on Quantum KNN Algorithm"
date: 2018-05-16 11:59:54
categories: arXiv_CV
tags: arXiv_CV Image_Classification Classification
author: Yijie Dang (1, 2 and 3), Nan Jiang (1, 2 and 3), Hao Hu (1, 2 and 3), Zhuoxiao Ji (1, 2 and 3), Wenyin Zhang (4) ((1) Faculty of Information Technology, Beijing University of Technology, Beijing, China (2) Beijing Key Laboratory of Trusted Computing, Beijing, China (3) National Engineering Laboratory for Critical Technologies of Information Security Classified Protection, Beijing, China (4) School of Information Science and Technology, Linyi University, Linyi, China)
mathjax: true
---

* content
{:toc}

##### Abstract
Image classification is an important task in the field of machine learning and image processing. However, the usually used classification method --- the K Nearest-Neighbor algorithm has high complexity, because its two main processes: similarity computing and searching are time-consuming. Especially in the era of big data, the problem is prominent when the amount of images to be classified is large. In this paper, we try to use the powerful parallel computing ability of quantum computers to optimize the efficiency of image classification. The scheme is based on quantum K Nearest-Neighbor algorithm. Firstly, the feature vectors of images are extracted on classical computers. Then the feature vectors are inputted into a quantum superposition state, which is used to achieve parallel computing of similarity. Next, the quantum minimum search algorithm is used to speed up searching process for similarity. Finally, the image is classified by quantum measurement. The complexity of the quantum algorithm is only O((kM)^(1/2)), which is superior to the classical algorithms. Moreover, the measurement step is executed only once to ensure the validity of the scheme. The experimental results show that, the classification accuracy is 83.1% on Graz-01 dataset and 78% on Caltech-101 dataset, which is close to existing classical algorithms. Hence, our quantum scheme has a good classification performance while greatly improving the efficiency.

##### Abstract (translated by Google)
图像分类是机器学习和图像处理领域的一项重要任务。然而，通常使用的分类方法--- K最近邻算法具有很高的复杂度，因为它的两个主要过程：相似性计算和搜索是耗时的。特别是在大数据时代，当要分类的图像数量很大时，问题突出。在本文中，我们试图利用量子计算机强大的并行计算能力来优化图像分类的效率。该方案基于量子K最近邻算法。首先，在经典计算机上提取图像的特征向量。然后将特征向量输入到量子叠加态，用于实现并行计算相似度。接下来，使用量子最小搜索算法来加速相似性的搜索过程。最后，图像通过量子测量进行分类。量子算法的复杂度仅为O（（kM）^（1/2）），优于经典算法。而且，测量步骤仅执行一次以确保方案的有效性。实验结果表明，Graz-01数据集的分类准确率为83.1％，Caltech-101数据集的分类准确率为78％，与已有的经典算法相近。因此，我们的量子方案具有良好的分类性能，同时大大提高了效率。

##### URL
[http://arxiv.org/abs/1805.06260](http://arxiv.org/abs/1805.06260)

##### PDF
[http://arxiv.org/pdf/1805.06260](http://arxiv.org/pdf/1805.06260)

