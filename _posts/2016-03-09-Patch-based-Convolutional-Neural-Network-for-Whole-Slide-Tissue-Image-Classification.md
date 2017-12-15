---
layout: post
title: "Patch-based Convolutional Neural Network for Whole Slide Tissue Image Classification"
date: 2016-03-09 14:26:16
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN Image_Classification Classification Prediction Relation
author: Le Hou, Dimitris Samaras, Tahsin M. Kurc, Yi Gao, James E. Davis, Joel H. Saltz
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Neural Networks (CNN) are state-of-the-art models for many image classification tasks. However, to recognize cancer subtypes automatically, training a CNN on gigapixel resolution Whole Slide Tissue Images (WSI) is currently computationally impossible. The differentiation of cancer subtypes is based on cellular-level visual features observed on image patch scale. Therefore, we argue that in this situation, training a patch-level classifier on image patches will perform better than or similar to an image-level classifier. The challenge becomes how to intelligently combine patch-level classification results and model the fact that not all patches will be discriminative. We propose to train a decision fusion model to aggregate patch-level predictions given by patch-level CNNs, which to the best of our knowledge has not been shown before. Furthermore, we formulate a novel Expectation-Maximization (EM) based method that automatically locates discriminative patches robustly by utilizing the spatial relationships of patches. We apply our method to the classification of glioma and non-small-cell lung carcinoma cases into subtypes. The classification accuracy of our method is similar to the inter-observer agreement between pathologists. Although it is impossible to train CNNs on WSIs, we experimentally demonstrate using a comparable non-cancer dataset of smaller images that a patch-based CNN can outperform an image-based CNN.

##### Abstract (translated by Google)
卷积神经网络（CNN）是许多图像分类任务的最新模型。然而，为了自动识别癌症亚型，在千兆像素分辨率上训练CNN整张幻灯片组织图像（WSI）目前在计算上是不可能的。癌症亚型的分化基于在图像斑块尺度上观察到的细胞水平的视觉特征。因此，我们认为在这种情况下，在图像块上训练一个补丁级分类器会比图像级分类器更好或者更好。挑战在于如何巧妙地将补丁级别的分类结果进行组合，并对不是所有补丁都具有区别性的事实进行建模。我们建议训练一个决策融合模型来汇总由补丁级CNN给出的补丁级预测，这在我们所知的最好的情况下还没有被显示过。此外，我们还制定了一种基于期望最大化（EM）的新方法，通过利用斑块的空间关系来自动地定位判别性斑块。我们应用我们的方法将胶质瘤和非小细胞肺癌病例分类为亚型。我们的方法的分类准确性与病理学家之间的观察者间的一致性相似。虽然在WSI上训练CNN是不可能的，但是我们通过实验证明，使用一个可比较的小型图像的非癌症数据集，基于补丁的CNN可以胜过基于图像的CNN。

##### URL
[https://arxiv.org/abs/1504.07947](https://arxiv.org/abs/1504.07947)

##### PDF
[https://arxiv.org/pdf/1504.07947](https://arxiv.org/pdf/1504.07947)

