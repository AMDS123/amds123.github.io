---
layout: post
title: "AFFACT - Alignment-Free Facial Attribute Classification Technique"
date: 2017-08-04 23:53:03
categories: arXiv_CV
tags: arXiv_CV Knowledge Face CNN Classification
author: Manuel Günther, Andras Rozsa, Terrance E. Boult
mathjax: true
---

* content
{:toc}

##### Abstract
Facial attributes are soft-biometrics that allow limiting the search space, e.g., by rejecting identities with non-matching facial characteristics such as nose sizes or eyebrow shapes. In this paper, we investigate how the latest versions of deep convolutional neural networks, ResNets, perform on the facial attribute classification task. We test two loss functions: the sigmoid cross-entropy loss and the Euclidean loss, and find that for classification performance there is little difference between these two. Using an ensemble of three ResNets, we obtain the new state-of-the-art facial attribute classification error of 8.00% on the aligned images of the CelebA dataset. More significantly, we introduce the Alignment-Free Facial Attribute Classification Technique (AFFACT), a data augmentation technique that allows a network to classify facial attributes without requiring alignment beyond detected face bounding boxes. To our best knowledge, we are the first to report similar accuracy when using only the detected bounding boxes -- rather than requiring alignment based on automatically detected facial landmarks -- and who can improve classification accuracy with rotating and scaling test images. We show that this approach outperforms the CelebA baseline on unaligned images with a relative improvement of 36.8%.

##### Abstract (translated by Google)
面部属性是允许限制搜索空间的软生物测量学，例如通过拒绝具有诸如鼻子大小或眉毛形状之类的不匹配面部特征的身份。在本文中，我们研究了最新版本的深度卷积神经网络ResNets如何执行面部属性分类任务。我们测试了两个损失函数：sigmoid交叉熵损失和欧几里德损失，发现对于分类性能，这两者之间几乎没有差别。使用三个ResNets的集合，我们在CelebA数据集的对齐的图像上获得8.00％的新的最新的面部属性分类错误。更重要的是，我们引入了无对齐面部属性分类技术（AFFACT），这是一种数据增强技术，允许网络对面部属性进行分类，而不需要在检测到的面部边界框之外对齐。据我们所知，我们是第一个在仅使用检测到的边界框时报告相似的精度 - 而不是要求基于自动检测的面部标志的对齐 - 谁可以通过旋转和缩放测试图像来提高分类准确度。我们发现这种方法胜过了未对齐图像上的CelebA基线，相对提高了36.8％。

##### URL
[https://arxiv.org/abs/1611.06158](https://arxiv.org/abs/1611.06158)

##### PDF
[https://arxiv.org/pdf/1611.06158](https://arxiv.org/pdf/1611.06158)

