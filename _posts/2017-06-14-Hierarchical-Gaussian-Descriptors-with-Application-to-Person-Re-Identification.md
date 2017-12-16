---
layout: post
title: "Hierarchical Gaussian Descriptors with Application to Person Re-Identification"
date: 2017-06-14 05:16:16
categories: arXiv_CV
tags: arXiv_CV Re-identification Person_Re-identification Embedding Image_Classification Classification
author: Tetsu Matsukawa, Takahiro Okabe, Einoshin Suzuki, Yoichi Sato
mathjax: true
---

* content
{:toc}

##### Abstract
Describing the color and textural information of a person image is one of the most crucial aspects of person re-identification (re-id). In this paper, we present novel meta-descriptors based on a hierarchical distribution of pixel features. Although hierarchical covariance descriptors have been successfully applied to image classification, the mean information of pixel features, which is absent from the covariance, tends to be the major discriminative information for person re-id. To solve this problem, we describe a local region in an image via hierarchical Gaussian distribution in which both means and covariances are included in their parameters. More specifically, the region is modeled as a set of multiple Gaussian distributions in which each Gaussian represents the appearance of a local patch. The characteristics of the set of Gaussians are again described by another Gaussian distribution. In both steps, we embed the parameters of the Gaussian into a point of Symmetric Positive Definite (SPD) matrix manifold. By changing the way to handle mean information in this embedding, we develop two hierarchical Gaussian descriptors. Additionally, we develop feature norm normalization methods with the ability to alleviate the biased trends that exist on the descriptors. The experimental results conducted on five public datasets indicate that the proposed descriptors achieve remarkably high performance on person re-id.

##### Abstract (translated by Google)
描述人物形象的颜色和纹理信息是人物重新识别（re-id）最关键的方面之一。在本文中，我们提出了基于像素特征的分层分布的新颖元描述符。尽管层次协方差描述符已经成功地应用于图像分类，但是协方差中缺少的像素特征的平均信息往往是人类重要的判别信息。为了解决这个问题，我们通过分层高斯分布在图像中描述局部区域，其中均值和协方差都包括在它们的参数中。更具体地说，该区域被建模为一组多个高斯分布，其中每个高斯代表一个局部区块的外观。高斯集的特征再次由另一个高斯分布描述。在这两个步骤中，我们将高斯参数嵌入到对称正定点（SPD）矩阵流形的一个点上。通过改变在这种嵌入中处理平均信息的方式，我们开发了两个分层的高斯描述符。另外，我们开发了特征规范归一化方法，能够缓解描述符上存在的偏向趋势。在五个公共数据集上进行的实验结果表明，所提出的描述符在人员重复性方面达到了非常高的性能。

##### URL
[https://arxiv.org/abs/1706.04318](https://arxiv.org/abs/1706.04318)

##### PDF
[https://arxiv.org/pdf/1706.04318](https://arxiv.org/pdf/1706.04318)

