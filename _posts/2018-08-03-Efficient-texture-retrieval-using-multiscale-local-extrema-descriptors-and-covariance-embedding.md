---
layout: post
title: "Efficient texture retrieval using multiscale local extrema descriptors and covariance embedding"
date: 2018-08-03 09:04:00
categories: arXiv_CV
tags: arXiv_CV Embedding
author: Minh-Tan Pham
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents an efficient method for texture retrieval using multiscale feature extraction and embedding based on the local extrema keypoints. The idea is to first represent each texture image by its local maximum and local minimum pixels. The image is then divided into regular overlapping blocks and each one is characterized by a feature vector constructed from the radiometric, geometric and structural information of its local extrema. All feature vectors are finally embedded into a covariance matrix which will be exploited for dissimilarity measurement within retrieval task. Thanks to the method's simplicity, multiscale scheme can be easily implemented to improve its scale-space representation capacity. We argue that our handcrafted features are easy to implement, fast to run but can provide very competitive performance compared to handcrafted and CNN-based learned descriptors from the literature. In particular, the proposed framework provides highly competitive retrieval rate for several texture databases including 94.95% for MIT Vistex, 79.87% for Stex, 76.15% for Outex TC-00013 and 89.74% for USPtex.

##### Abstract (translated by Google)
本文提出了一种基于局部极值关键点的多尺度特征提取和嵌入的有效纹理检索方法。想法是首先通过其局部最大和局部最小像素来表示每个纹理图像。然后将图像分成规则的重叠块，每个块的特征在于由其局部极值的辐射度，几何和结构信息构成的特征向量。最后将所有特征向量嵌入到协方差矩阵中，该矩阵将被用于检索任务内的不相似度量。由于该方法的简单性，可以容易地实现多尺度方案以改善其尺度空间表示能力。我们认为，与文献中的手工制作和基于CNN的学习描述符相比，我们的手工制作功能易于实现，运行速度快，但可以提供极具竞争力的性能。特别是，拟议框架为几个纹理数据库提供了极具竞争力的检索率，其中MIT Vistex为94.95％，Stex为79.87％，Outex TC-00013为76.15％，USPtex为89.74％。

##### URL
[http://arxiv.org/abs/1808.01124](http://arxiv.org/abs/1808.01124)

##### PDF
[http://arxiv.org/pdf/1808.01124](http://arxiv.org/pdf/1808.01124)

