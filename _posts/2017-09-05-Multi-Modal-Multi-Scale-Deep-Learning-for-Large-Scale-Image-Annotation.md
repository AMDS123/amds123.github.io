---
layout: post
title: "Multi-Modal Multi-Scale Deep Learning for Large-Scale Image Annotation"
date: 2017-09-05 02:50:45
categories: arXiv_CV
tags: arXiv_CV Attention RNN Classification Deep_Learning Prediction
author: Yulei Niu, Zhiwu Lu, Ji-Rong Wen, Tao Xiang, Shih-Fu Chang
mathjax: true
---

* content
{:toc}

##### Abstract
Large-scale image annotation is a challenging task in image content analysis, which aims to annotate each image of a very large dataset with multiple class labels. In this paper, we focus on two main issues in large-scale image annotation: 1) how to learn stronger features for multifarious images; 2) how to annotate an image with an automatically-determined number of class labels. To address the first issue, we propose a multi-modal multi-scale deep learning model for extracting descriptive features from multifarious images. Specifically, the visual features extracted by a multi-scale deep learning subnetwork are refined with the textual features extracted from social tags along with images by a simple multi-layer perception subnetwork. Since we have extracted very powerful features by multi-modal multi-scale deep learning, we simplify the second issue and decompose large-scale image annotation into multi-class classification and label quantity prediction. Note that the label quantity prediction subproblem can be implicitly solved when a recurrent neural network (RNN) model is used for image annotation. However, in this paper, we choose to explicitly solve this subproblem directly using our deep learning model, resulting in that we can pay more attention to deep feature learning. Experimental results demonstrate the superior performance of our model as compared to the state-of-the-art (including RNN-based models).

##### Abstract (translated by Google)
大规模的图像标注是图像内容分析中的一个具有挑战性的任务，其目的是用多个类别标注来标注每个非常大的数据集的图像。本文重点研究大规模图像标注中的两个主要问题：1）如何为多种图像学习更强的特征; 2）如何使用自动确定的类标签数量对图像进行注释。为了解决第一个问题，我们提出了一个多模态多尺度深度学习模型，从多种图像中提取描述性特征。具体而言，多尺度深度学习子网络提取的视觉特征通过简单的多层感知子网络从社交标签提取的文本特征与图像一起被细化。由于我们通过多模态多尺度深度学习提取了非常强大的特征，我们简化了第二个问题，将大规模图像标注分解为多类分类和标注数量预测。注意，当使用递归神经网络（RNN）模型进行图像注释时，可以隐式地解决标签数量预测子问题。然而，在本文中，我们选择使用我们的深度学习模型直接明确地解决这个子问题，导致我们可以更多地关注深度特征学习。实验结果表明，与现有技术（包括基于RNN的模型）相比，我们的模型具有优越的性能。

##### URL
[https://arxiv.org/abs/1709.01220](https://arxiv.org/abs/1709.01220)

##### PDF
[https://arxiv.org/pdf/1709.01220](https://arxiv.org/pdf/1709.01220)

