---
layout: post
title: "Natural Scene Recognition Based on Superpixels and Deep Boltzmann Machines"
date: 2015-06-24 07:53:54
categories: arXiv_CV
tags: arXiv_CV Recognition
author: Jinfu Yang, Jingyu Gao, Guanghui Wang, Shanshan Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
The Deep Boltzmann Machines (DBM) is a state-of-the-art unsupervised learning model, which has been successfully applied to handwritten digit recognition and, as well as object recognition. However, the DBM is limited in scene recognition due to the fact that natural scene images are usually very large. In this paper, an efficient scene recognition approach is proposed based on superpixels and the DBMs. First, a simple linear iterative clustering (SLIC) algorithm is employed to generate superpixels of input images, where each superpixel is regarded as an input of a learning model. Then, a two-layer DBM model is constructed by stacking two restricted Boltzmann machines (RBMs), and a greedy layer-wise algorithm is applied to train the DBM model. Finally, a softmax regression is utilized to categorize scene images. The proposed technique can effectively reduce the computational complexity and enhance the performance for large natural image recognition. The approach is verified and evaluated by extensive experiments, including the fifteen-scene categories dataset the UIUC eight-sports dataset, and the SIFT flow dataset, are used to evaluate the proposed method. The experimental results show that the proposed approach outperforms other state-of-the-art methods in terms of recognition rate.

##### Abstract (translated by Google)
深玻尔兹曼机（DBM）是一种最先进的无监督学习模型，已经成功地应用于手写体数字识别和物体识别。然而，由于自然景物图像通常非常大，所以DBM在场景识别方面受到限制。本文提出了一种基于超像素和DBM的高效场景识别方法。首先，采用简单的线性迭代聚类（SLIC）算法来生成输入图像的超像素，其中每个超像素被视为学习模型的输入。然后，通过叠加两个受限玻尔兹曼机（RBM）构建一个双层DBM模型，并采用贪心分层算法训练DBM模型。最后，使用softmax回归对场景图像进行分类。所提出的技术能够有效地降低计算复杂度，提高大型自然图像识别的性能。该方法通过大量的实验验证和评估，包括十五个场景类别数据集UIUC八个体育数据集和SIFT流数据集，用于评估所提出的方法。实验结果表明，所提出的方法在识别率方面优于其他最先进的方法。

##### URL
[https://arxiv.org/abs/1506.07271](https://arxiv.org/abs/1506.07271)

##### PDF
[https://arxiv.org/pdf/1506.07271](https://arxiv.org/pdf/1506.07271)

