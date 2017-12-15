---
layout: post
title: "Sub-cortical brain structure segmentation using F-CNN's"
date: 2016-02-05 19:32:39
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Inference Deep_Learning
author: Mahsa Shakeri, Stavros Tsogkas (CVN, GALEN), Enzo Ferrante (CVN, GALEN), Sarah Lippe, Samuel Kadoury, Nikos Paragios (CVN, GALEN), Iasonas Kokkinos (CVN, GALEN)
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we propose a deep learning approach for segmenting sub-cortical structures of the human brain in Magnetic Resonance (MR) image data. We draw inspiration from a state-of-the-art Fully-Convolutional Neural Network (F-CNN) architecture for semantic segmentation of objects in natural images, and adapt it to our task. Unlike previous CNN-based methods that operate on image patches, our model is applied on a full blown 2D image, without any alignment or registration steps at testing time. We further improve segmentation results by interpreting the CNN output as potentials of a Markov Random Field (MRF), whose topology corresponds to a volumetric grid. Alpha-expansion is used to perform approximate inference imposing spatial volumetric homogeneity to the CNN priors. We compare the performance of the proposed pipeline with a similar system using Random Forest-based priors, as well as state-of-art segmentation algorithms, and show promising results on two different brain MRI datasets.

##### Abstract (translated by Google)
在本文中，我们提出了一种深入的学习方法来分割磁共振（MR）图像数据中的人脑的亚皮质结构。我们从最先进的全卷积神经网络（F-CNN）架构中获取灵感，用于自然图像中物体的语义分割，并将其与我们的任务相适应。与以前的基于CNN的图像补丁方法不同，我们的模型应用于完整的2D图像，在测试时没有任何对齐或配准步骤。通过将CNN输出解释为马尔可夫随机场（MRF）的电势，其拓扑对应于体积网格，我们进一步改善了分割结果。 Alpha扩展被用来执行逼近推理，强制CNN先验空间体积均匀性。我们比较了所提出的管道与使用基于随机森林的先验的类似系统的性能以及最先进的分割算法，并且在两个不同的脑MRI数据集上显示出有希望的结果。

##### URL
[https://arxiv.org/abs/1602.02130](https://arxiv.org/abs/1602.02130)

##### PDF
[https://arxiv.org/pdf/1602.02130](https://arxiv.org/pdf/1602.02130)

