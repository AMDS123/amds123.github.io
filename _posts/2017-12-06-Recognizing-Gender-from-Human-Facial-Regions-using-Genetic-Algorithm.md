---
layout: post
title: 'Recognizing Gender from Human Facial Regions using Genetic Algorithm'
date: 2017-12-06 10:01:55
categories: arXiv_CV
tags: arXiv_CV Recognition
author: Avirup Bhattacharyya, Rajkumar Saini, Partha Pratim Roy, Debi Prosad Dogra, Samarjit Kar
---

* content
{:toc}

##### Abstract
Recently, recognition of gender from facial images has gained a lot of importance. There exist a handful of research work that focus on feature extraction to obtain gender specific information from facial images. However, analyzing different facial regions and their fusion help in deciding the gender of a person from facial images. In this paper, we propose a new approach to identify gender from frontal facial images that is robust to background, illumination, intensity, and facial expression. In our framework, first the frontal face image is divided into a number of distinct regions based on facial landmark points that are obtained by the Chehra model proposed by Asthana et al. The model provides 49 facial landmark points covering different regions of the face, e.g. forehead, left eye, right eye, lips. Next, a face image is segmented into facial regions using landmark points and features are extracted from each region. The Compass LBP feature, a variant of LBP feature, has been used in our framework to obtain discriminative gender-specific information. Following this, a Support Vector Machine based classifier has been used to compute the probability scores from each facial region. Finally, the classification scores obtained from individual regions are combined with a genetic algorithm based learning to improve the overall classification accuracy. The experiments have been performed on popular face image datasets such as Adience, cFERET (color FERET), LFW and two sketch datasets, namely CUFS and CUFSF. Through experiments, we have observed that, the proposed method outperforms existing approaches.

##### Abstract (translated by Google)
最近，从面部图像中识别性别已经变得非常重要。目前有一些研究工作集中于特征提取从面部图像获取性别特定信息。然而，分析不同的面部区域及其融合有助于从面部图像中确定人的性别。在本文中，我们提出了一种新的方法来识别正面的面部图像的性别，对背景，光照，强度和面部表情是强健的。在我们的框架中，首先根据Asthana等人提出的Chehra模型得到的面部标志点将正面人脸图像划分为多个不同的区域。该模型提供了覆盖脸部不同区域的49个面部标志点，例如，额头，左眼，右眼，嘴唇。接下来，使用界标点将脸部图像分割成脸部区域，并且从每个区域提取特征。在我们的框架中已经使用了指南针LBP特征（LBP特征的变体）来获得区分性别的特定信息。之后，使用基于支持向量机的分类器来计算来自每个面部区域的概率分数。最后，从个别地区获得的分类分数与基于遗传算法的学习相结合，以提高整体分类的准确性。在Adience，cFERET（color FERET），LFW和两个素描数据集CUFS和CUFSF等流行的人脸图像数据集上进行了实验。通过实验，我们观察到，所提出的方法优于现有的方法。

##### URL
[https://arxiv.org/abs/1712.01661](https://arxiv.org/abs/1712.01661)

