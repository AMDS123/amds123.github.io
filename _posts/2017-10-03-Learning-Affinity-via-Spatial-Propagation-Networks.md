---
layout: post
title: "Learning Affinity via Spatial Propagation Networks"
date: 2017-10-03 08:00:15
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation Face Semantic_Segmentation Relation
author: Sifei Liu, Shalini De Mello, Jinwei Gu, Guangyu Zhong, Ming-Hsuan Yang, Jan Kautz
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose spatial propagation networks for learning the affinity matrix for vision tasks. We show that by constructing a row/column linear propagation model, the spatially varying transformation matrix exactly constitutes an affinity matrix that models dense, global pairwise relationships of an image. Specifically, we develop a three-way connection for the linear propagation model, which (a) formulates a sparse transformation matrix, where all elements can be the output from a deep CNN, but (b) results in a dense affinity matrix that effectively models any task-specific pairwise similarity matrix. Instead of designing the similarity kernels according to image features of two points, we can directly output all the similarities in a purely data-driven manner. The spatial propagation network is a generic framework that can be applied to many affinity-related tasks, including but not limited to image matting, segmentation and colorization, to name a few. Essentially, the model can learn semantically-aware affinity values for high-level vision tasks due to the powerful learning capability of the deep neural network classifier. We validate the framework on the task of refinement for image segmentation boundaries. Experiments on the HELEN face parsing and PASCAL VOC-2012 semantic segmentation tasks show that the spatial propagation network provides a general, effective and efficient solution for generating high-quality segmentation results.

##### Abstract (translated by Google)
在本文中，我们提出了用于学习视觉任务的亲和矩阵的空间传播网络。我们表明通过构建行/列线性传播模型，空间变化的变换矩阵准确地构成了模拟图像的密集的全局成对关系的亲和力矩阵。具体来说，我们为线性传播模型建立了三维连接，其中（a）制定稀疏变换矩阵，其中所有元素可以是来自深度CNN的输出，但是（b）产生密集的亲和力矩阵，其有效地建模任何特定于任务的成对相似性矩阵。不是根据两点的图像特征来设计相似性核，而是直接以纯数据驱动的方式输出所有的相似性。空间传播网络是一个通用的框架，可以应用于许多亲和力相关的任务，包括但不限于图像抠像，分割和着色等等。本质上，由于深度神经网络分类器的强大学习能力，该模型可以学习高级视觉任务的语义感知亲和力值。我们验证框架的细化任务的图像分割边界。 HELEN人脸解析和PASCAL VOC-2012语义分割任务的实验表明，空间传播网络为生成高质量的分割结果提供了一个通用，有效和高效的解决方案。

##### URL
[https://arxiv.org/abs/1710.01020](https://arxiv.org/abs/1710.01020)

##### PDF
[https://arxiv.org/pdf/1710.01020](https://arxiv.org/pdf/1710.01020)

