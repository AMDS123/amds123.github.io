---
layout: post
title: "A General Framework for Multi-focal Image Classification and Authentication: Application to Microscope Pollen Images"
date: 2015-03-19 14:44:29
categories: arXiv_CV
tags: arXiv_CV Segmentation Image_Classification Classification
author: François Chung, Tomás Rodríguez
mathjax: true
---

* content
{:toc}

##### Abstract
In this article, we propose a general framework for multi-focal image classification and authentication, the methodology being demonstrated on microscope pollen images. The framework is meant to be generic and based on a brute force-like approach aimed to be efficient not only on any kind, and any number, of pollen images (regardless of the pollen type), but also on any kind of multi-focal images. All stages of the framework's pipeline are designed to be used in an automatic fashion. First, the optimal focus is selected using the absolute gradient method. Then, pollen grains are extracted using a coarse-to-fine approach involving both clustering and morphological techniques (coarse stage), and a snake-based segmentation (fine stage). Finally, features are extracted and selected using a generalized approach, and their classification is tested with four classifiers: Weighted Neighbor Distance, Neural Network, Decision Tree and Random Forest. The latter method, which has shown the best and more robust classification accuracy results (above 97\% for any number of pollen types), is finally used for the authentication stage.

##### Abstract (translated by Google)
在本文中，我们提出了一个多焦点图像分类和认证的一般框架，在显微镜花粉图像上展示了这种方法。该框架是通用的，基于强力的方法，旨在不仅对任何种类，任何数量的花粉图像（不论花粉类型），还对任何类型的多焦点图片。框架流水线的所有阶段都被设计为以自动方式使用。首先，使用绝对梯度法来选择最佳焦点。然后，使用从粗到细的方法（包括聚类和形态学技术（粗糙阶段）和基于蛇的分割（精细阶段））提取花粉粒。最后，采用广义方法提取和选择特征，并用四个分类器进行分类：加权邻接距离，神经网络，决策树和随机森林。后一种方法已经显示出最好和更稳健的分类准确性结果（任何数量的花粉类型超过97％），最终被用于认证阶段。

##### URL
[https://arxiv.org/abs/1503.05786](https://arxiv.org/abs/1503.05786)

##### PDF
[https://arxiv.org/pdf/1503.05786](https://arxiv.org/pdf/1503.05786)

