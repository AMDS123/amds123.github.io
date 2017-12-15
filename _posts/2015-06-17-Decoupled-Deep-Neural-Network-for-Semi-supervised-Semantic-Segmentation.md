---
layout: post
title: "Decoupled Deep Neural Network for Semi-supervised Semantic Segmentation"
date: 2015-06-17 08:38:32
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Classification
author: Seunghoon Hong, Hyeonwoo Noh, Bohyung Han
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel deep neural network architecture for semi-supervised semantic segmentation using heterogeneous annotations. Contrary to existing approaches posing semantic segmentation as a single task of region-based classification, our algorithm decouples classification and segmentation, and learns a separate network for each task. In this architecture, labels associated with an image are identified by classification network, and binary segmentation is subsequently performed for each identified label in segmentation network. The decoupled architecture enables us to learn classification and segmentation networks separately based on the training data with image-level and pixel-wise class labels, respectively. It facilitates to reduce search space for segmentation effectively by exploiting class-specific activation maps obtained from bridging layers. Our algorithm shows outstanding performance compared to other semi-supervised approaches even with much less training images with strong annotations in PASCAL VOC dataset.

##### Abstract (translated by Google)
我们提出了一个新的深度神经网络架构半监督语义分割使用异构注释。与将语义分割作为区域分类单一任务的现有方法相反，我们的算法对分类和分割进行解耦，并为每个任务学习单独的网络。在该体系结构中，分类网络识别与图像相关联的标签，并且随后对分割网络中的每个识别的标签执行二进制分割。分离的架构使我们能够分别根据训练数据分别学习分类和分割网络，分别使用图像级和像素级分类标签。它有助于通过利用从桥接层获得的特定于类的激活映射来有效地减少用于分割的搜索空间。与其他半监督方法相比，我们的算法显示了出色的表现，即使在PASCAL VOC数据集中具有较强的注释的训练图像也少得多。

##### URL
[https://arxiv.org/abs/1506.04924](https://arxiv.org/abs/1506.04924)

##### PDF
[https://arxiv.org/pdf/1506.04924](https://arxiv.org/pdf/1506.04924)

