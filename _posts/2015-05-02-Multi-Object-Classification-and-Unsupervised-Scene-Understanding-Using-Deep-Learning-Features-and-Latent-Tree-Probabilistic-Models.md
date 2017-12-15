---
layout: post
title: "Multi-Object Classification and Unsupervised Scene Understanding Using Deep Learning Features and Latent Tree Probabilistic Models"
date: 2015-05-02 03:23:46
categories: arXiv_CV
tags: arXiv_CV Inference Classification Deep_Learning
author: Tejaswi Nimmagadda, Anima Anandkumar
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning has shown state-of-art classification performance on datasets such as ImageNet, which contain a single object in each image. However, multi-object classification is far more challenging. We present a unified framework which leverages the strengths of multiple machine learning methods, viz deep learning, probabilistic models and kernel methods to obtain state-of-art performance on Microsoft COCO, consisting of non-iconic images. We incorporate contextual information in natural images through a conditional latent tree probabilistic model (CLTM), where the object co-occurrences are conditioned on the extracted fc7 features from pre-trained Imagenet CNN as input. We learn the CLTM tree structure using conditional pairwise probabilities for object co-occurrences, estimated through kernel methods, and we learn its node and edge potentials by training a new 3-layer neural network, which takes fc7 features as input. Object classification is carried out via inference on the learnt conditional tree model, and we obtain significant gain in precision-recall and F-measures on MS-COCO, especially for difficult object categories. Moreover, the latent variables in the CLTM capture scene information: the images with top activations for a latent node have common themes such as being a grasslands or a food scene, and on on. In addition, we show that a simple k-means clustering of the inferred latent nodes alone significantly improves scene classification performance on the MIT-Indoor dataset, without the need for any retraining, and without using scene labels during training. Thus, we present a unified framework for multi-object classification and unsupervised scene understanding.

##### Abstract (translated by Google)
深度学习在数据集（如ImageNet）上显示了最先进的分类性能，在每个图像中包含一个对象。但是，多对象分类更具挑战性。我们提出了一个统一的框架，利用多种机器学习方法，即深度学习，概率模型和内核方法的优势，获得微软COCO上最先进的性能，包括非图标图像。我们通过一个条件潜在树概率模型（CLTM）将自然图像中的上下文信息结合起来，其中对象共现以提取的fc7特征作为输入，从预先训练好的Imagenet CNN中提取。我们学习CLTM树结构使用条件成对概率的对象共现，通过核方法估计，我们通过训练一个新的三层神经网络，它采用fc7功能作为输入，了解其节点和边缘潜力。通过对学习的条件树模型的推理进行对象分类，在MS-COCO上，尤其对于困难的对象类别，我们获得了显着的精确召回和F-measure的增益。此外，CLTM捕捉场景信息中的潜在变量：具有潜在节点的最高激活的图像具有诸如草地或食物场景等共同的主题，等等。此外，我们表明，简单的k-means聚类的推断潜在节点本身显着提高麻省理工学院室内数据集的场景分类性能，无需任何再培训，并且在训练期间不使用场景标签。因此，我们提出了一个多对象分类和无监督场景理解的统一框架。

##### URL
[https://arxiv.org/abs/1505.00308](https://arxiv.org/abs/1505.00308)

##### PDF
[https://arxiv.org/pdf/1505.00308](https://arxiv.org/pdf/1505.00308)

