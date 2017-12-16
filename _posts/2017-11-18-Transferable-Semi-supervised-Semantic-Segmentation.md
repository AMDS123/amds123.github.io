---
layout: post
title: "Transferable Semi-supervised Semantic Segmentation"
date: 2017-11-18 08:56:06
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge Segmentation Semantic_Segmentation Deep_Learning Prediction
author: Huaxin Xiao, Yunchao Wei, Yu Liu, Maojun Zhang, Jiashi Feng
mathjax: true
---

* content
{:toc}

##### Abstract
The performance of deep learning based semantic segmentation models heavily depends on sufficient data with careful annotations. However, even the largest public datasets only provide samples with pixel-level annotations for rather limited semantic categories. Such data scarcity critically limits scalability and applicability of semantic segmentation models in real applications. In this paper, we propose a novel transferable semi-supervised semantic segmentation model that can transfer the learned segmentation knowledge from a few strong categories with pixel-level annotations to unseen weak categories with only image-level annotations, significantly broadening the applicable territory of deep segmentation models. In particular, the proposed model consists of two complementary and learnable components: a Label transfer Network (L-Net) and a Prediction transfer Network (P-Net). The L-Net learns to transfer the segmentation knowledge from strong categories to the images in the weak categories and produces coarse pixel-level semantic maps, by effectively exploiting the similar appearance shared across categories. Meanwhile, the P-Net tailors the transferred knowledge through a carefully designed adversarial learning strategy and produces refined segmentation results with better details. Integrating the L-Net and P-Net achieves 96.5% and 89.4% performance of the fully-supervised baseline using 50% and 0% categories with pixel-level annotations respectively on PASCAL VOC 2012. With such a novel transfer mechanism, our proposed model is easily generalizable to a variety of new categories, only requiring image-level annotations, and offers appealing scalability in real applications.

##### Abstract (translated by Google)
基于深度学习的语义分割模型的性能在很大程度上取决于充足的数据和仔细的注释。然而，即使是最大的公共数据集也只能提供像素级注释的样本，而只能使用相当有限的语义类别。这种数据稀缺严重限制了语义分割模型在实际应用中的可扩展性和适用性。在本文中，我们提出了一种新的可移植的半监督语义分割模型，可以将学习到的分割知识从几个具有像素级注释的强类别转移到只有图像级注释的弱类别，显着拓宽了深度适用领域细分模型。具体而言，所提出的模型由两个互补且可学习的组件组成：标签传输网络（L-Net）和预测传输网络（P-Net）。 L-Net学习将分类知识从强类别转移到弱类别的图像，并通过有效利用跨类别共享的相似外观，生成粗糙的像素级语义地图。同时，P-Net通过精心设计的对抗性学习策略来调整传递的知识，并生成更细致的细化结果。在PASCAL VOC 2012中，L-Net和P-Net的集成度分别达到了完全监督基线的96.5％和89.4％，分别使用了50％和0％的像素级注释类别。利用这种新颖的传输机制，很容易推广到各种新类别，只需要图像级别的注释，并且在实际应用中提供了吸引人的可扩展性。

##### URL
[https://arxiv.org/abs/1711.06828](https://arxiv.org/abs/1711.06828)

##### PDF
[https://arxiv.org/pdf/1711.06828](https://arxiv.org/pdf/1711.06828)

