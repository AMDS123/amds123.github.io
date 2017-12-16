---
layout: post
title: "k-Means Clustering and Ensemble of Regressions: An Algorithm for the ISIC 2017 Skin Lesion Segmentation Challenge"
date: 2017-02-23 18:43:30
categories: arXiv_CV
tags: arXiv_CV Segmentation Detection
author: David Alvarez, Monica Iglesias
mathjax: true
---

* content
{:toc}

##### Abstract
This abstract briefly describes a segmentation algorithm developed for the ISIC 2017 Skin Lesion Detection Competition hosted at [ref]. The objective of the competition is to perform a segmentation (in the form of a binary mask image) of skin lesions in dermoscopic images as close as possible to a segmentation performed by trained clinicians, which is taken as ground truth. This project only takes part in the segmentation phase of the challenge. The other phases of the competition (feature extraction and lesion identification) are not considered. The proposed algorithm consists of 4 steps: (1) lesion image preprocessing, (2) image segmentation using k-means clustering of pixel colors, (3) calculation of a set of features describing the properties of each segmented region, and (4) calculation of a final score for each region, representing the likelihood of corresponding to a suitable lesion segmentation. The scores in step (4) are obtained by averaging the results of 2 different regression models using the scores of each region as input. Before using the algorithm these regression models must be trained using the training set of images and ground truth masks provided by the Competition. Steps 2 to 4 are repeated with an increasing number of clusters (and therefore the image is segmented into more regions) until there is no further improvement of the calculated scores.

##### Abstract (translated by Google)
本摘要简要介绍了为[参考文献]举办的“ISIC 2017皮肤病变检测竞赛”开发的分割算法。比赛的目的是尽可能接近由训练有素的临床医生进行的分割，将真皮图像中的皮肤损伤分割（以二进制蒙版图像的形式），作为基础事实。这个项目只参与挑战的细分阶段。没有考虑竞争的其他阶段（特征提取和病变识别）。该算法由4个步骤组成：（1）病灶图像预处理;（2）使用像素颜色的k均值聚类的图像分割;（3）计算描述每个分割区域的特性的一组特征;以及（4）计算每个区域的最终得分，表示对应于合适的病灶分割的可能性。步骤（4）中的得分是通过使用每个区域的得分作为输入来平均2个不同回归模型的结果而获得的。在使用该算法之前，必须使用由比赛提供的图像训练集和地面实况面具来训练这些回归模型。步骤2到步骤4以越来越多的聚类重复（因此图像被分割成更多的区域），直到计算得分没有进一步的改善。

##### URL
[https://arxiv.org/abs/1702.07333](https://arxiv.org/abs/1702.07333)

##### PDF
[https://arxiv.org/pdf/1702.07333](https://arxiv.org/pdf/1702.07333)

