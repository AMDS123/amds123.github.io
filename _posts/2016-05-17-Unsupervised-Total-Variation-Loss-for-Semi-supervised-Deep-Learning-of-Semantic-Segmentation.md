---
layout: post
title: "Unsupervised Total Variation Loss for Semi-supervised Deep Learning of Semantic Segmentation"
date: 2016-05-17 20:46:35
categories: arXiv_CV
tags: arXiv_CV Regularization Segmentation CNN Semantic_Segmentation Deep_Learning
author: Mehran Javanmardi, Mehdi Sajjadi, Ting Liu, Tolga Tasdizen
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a novel unsupervised loss function for learning semantic segmentation with deep convolutional neural nets (ConvNet) when densely labeled training images are not available. More specifically, the proposed loss function penalizes the L1-norm of the gradient of the label probability vector image , i.e. total variation, produced by the ConvNet. This can be seen as a regularization term that promotes piecewise smoothness of the label probability vector image produced by the ConvNet during learning. The unsupervised loss function is combined with a supervised loss in a semi-supervised setting to learn ConvNets that can achieve high semantic segmentation accuracy even when only a tiny percentage of the pixels in the training images are labeled. We demonstrate significant improvements over the purely supervised setting in the Weizmann horse, Stanford background and Sift Flow datasets. Furthermore, we show that using the proposed piecewise smoothness constraint in the learning phase significantly outperforms post-processing results from a purely supervised approach with Markov Random Fields (MRF). Finally, we note that the framework we introduce is general and can be used to learn to label other types of structures such as curvilinear structures by modifying the unsupervised loss function accordingly.

##### Abstract (translated by Google)
当密集标记的训练图像不可用时，我们引入一种新的无监督损失函数用于学习深卷积神经网络（ConvNet）的语义分割。更具体地说，所提出的损失函数惩罚由ConvNet产生的标签概率向量图像的梯度的L1范数，即总变差。这可以看作是一个正则化术语，它促进了ConvNet在学习过程中产生的标签概率矢量图像的分段平滑。将无监督损失函数与半监督设置中的监督损失相结合，以学习能够实现高语义分割准确度的ConvNets，即使训练图像中只有很小比例的像素被标记。我们证明了Weizmann马，Stanford背景和Sift Flow数据集中的纯监督环境的显着改进。此外，我们表明，在学习阶段使用建议的分段平滑约束显着优于纯监督方法与马尔可夫随机场（MRF）的后处理结果。最后，我们注意到我们引入的框架是一般的，可以用来通过相应地修改无监督损失函数来学习标记其他类型的结构，如曲线结构。

##### URL
[https://arxiv.org/abs/1605.01368](https://arxiv.org/abs/1605.01368)

##### PDF
[https://arxiv.org/pdf/1605.01368](https://arxiv.org/pdf/1605.01368)

