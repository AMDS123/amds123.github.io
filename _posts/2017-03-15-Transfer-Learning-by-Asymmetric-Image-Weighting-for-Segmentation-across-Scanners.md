---
layout: post
title: "Transfer Learning by Asymmetric Image Weighting for Segmentation across Scanners"
date: 2017-03-15 07:43:10
categories: arXiv_CV
tags: arXiv_CV Segmentation Transfer_Learning Classification
author: Veronika Cheplygina, Annegreet van Opbroek, M. Arfan Ikram, Meike W. Vernooij, Marleen de Bruijne
mathjax: true
---

* content
{:toc}

##### Abstract
Supervised learning has been very successful for automatic segmentation of images from a single scanner. However, several papers report deteriorated performances when using classifiers trained on images from one scanner to segment images from other scanners. We propose a transfer learning classifier that adapts to differences between training and test images. This method uses a weighted ensemble of classifiers trained on individual images. The weight of each classifier is determined by the similarity between its training image and the test image. We examine three unsupervised similarity measures, which can be used in scenarios where no labeled data from a newly introduced scanner or scanning protocol is available. The measures are based on a divergence, a bag distance, and on estimating the labels with a clustering procedure. These measures are asymmetric. We study whether the asymmetry can improve classification. Out of the three similarity measures, the bag similarity measure is the most robust across different studies and achieves excellent results on four brain tissue segmentation datasets and three white matter lesion segmentation datasets, acquired at different centers and with different scanners and scanning protocols. We show that the asymmetry can indeed be informative, and that computing the similarity from the test image to the training images is more appropriate than the opposite direction.

##### Abstract (translated by Google)
监督学习对于从单个扫描仪自动分割图像已经非常成功。然而，有几篇论文报告使用一台扫描仪的图像训练分类器来分割来自其他扫描仪的图像时性能恶化。我们提出了一个转移学习分类器，适应训练和测试图像之间的差异。该方法使用在单个图像上训练的加权分类器集合。每个分类器的权重由其训练图像和测试图像之间的相似度确定。我们研究了三种无监督的相似性度量，这种度量可以在没有新引入的扫描仪或扫描协议的标记数据可用的情况下使用。这些措施是基于分歧，袋子距离以及通过聚类程序估计标签。这些措施是不对称的。我们研究是否不对称可以改善分类。在三个相似性测量中，袋子相似性度量在不同研究中是最稳健的，并且在四个脑组织分割数据集和三个白质病变分割数据集中获得了优异的结果，这些数据集在不同中心和不同扫描仪和扫描协议获得。我们表明，不对称确实可以提供信息，并且从测试图像到训练图像的相似性计算比相反的方向更合适。

##### URL
[https://arxiv.org/abs/1703.04981](https://arxiv.org/abs/1703.04981)

##### PDF
[https://arxiv.org/pdf/1703.04981](https://arxiv.org/pdf/1703.04981)

