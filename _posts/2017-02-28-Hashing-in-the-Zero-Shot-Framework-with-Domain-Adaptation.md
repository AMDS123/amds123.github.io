---
layout: post
title: "Hashing in the Zero Shot Framework with Domain Adaptation"
date: 2017-02-28 19:43:41
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Optimization
author: Shubham Pachori, Ameya Deshpande, Shanmuganathan Raman
mathjax: true
---

* content
{:toc}

##### Abstract
Techniques to learn hash codes which can store and retrieve large dimensional multimedia data efficiently have attracted broad research interests in the recent years. With rapid explosion of newly emerged concepts and online data, existing supervised hashing algorithms suffer from the problem of scarcity of ground truth annotations due to the high cost of obtaining manual annotations. Therefore, we propose an algorithm to learn a hash function from training images belonging to `seen' classes which can efficiently encode images of `unseen' classes to binary codes. Specifically, we project the image features from visual space and semantic features from semantic space into a common Hamming subspace. Earlier works to generate hash codes have tried to relax the discrete constraints on hash codes and solve the continuous optimization problem. However, it often leads to quantization errors. In this work, we use the max-margin classifier to learn an efficient hash function. To address the concern of domain-shift which may arise due to the introduction of new classes, we also introduce an unsupervised domain adaptation model in the proposed hashing framework. Results on the three datasets show the advantage of using domain adaptation in learning a high-quality hash function and superiority of our method for the task of image retrieval performance as compared to several state-of-the-art hashing methods.

##### Abstract (translated by Google)
学习可以有效存储和检索大尺寸多媒体数据的散列码技术近年来引起了广泛的研究兴趣。随着新兴概念和在线数据的迅速爆发，现有的监督哈希算法由于获取手工注释的成本高昂而遭受地面真实注释缺乏的问题。因此，我们提出了一种算法来从属于“可见”类别的训练图像中学习散列函数，该类别能够有效地将“不可见”类的图像编码为二进制代码。具体而言，我们将从视觉空间和语义特征的图像特征从语义空间投影到共同的汉明子空间。早期的工作是生成哈希码，试图放宽哈希码的离散约束，并解决连续优化问题。但是，这往往会导致量化误差。在这项工作中，我们使用最大边缘分类器学习一个有效的散列函数。为了解决由于引入新类而引起的域转移问题，我们还在所提出的散列框架中引入了无监督域自适应模型。三个数据集上的结果显示，与一些最先进的散列方法相比，使用域自适应学习高质量散列函数的优势以及我们方法在图像检索性能方面的优越性。

##### URL
[https://arxiv.org/abs/1702.01933](https://arxiv.org/abs/1702.01933)

##### PDF
[https://arxiv.org/pdf/1702.01933](https://arxiv.org/pdf/1702.01933)

