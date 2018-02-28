---
layout: post
title: "Directional Statistics-based Deep Metric Learning for Image Classification and Retrieval"
date: 2018-02-27 00:54:19
categories: arXiv_CV
tags: arXiv_CV Embedding CNN Image_Classification Classification
author: Xuefei Zhe, Shifeng Chen, Hong Yan
mathjax: true
---

* content
{:toc}

##### Abstract
Deep distance metric learning (DDML), which is proposed to learn image similarity metrics in an end-to-end manner based on the convolution neural network, has achieved encouraging results in many computer vision tasks.$L2$-normalization in the embedding space has been used to improve the performance of several DDML methods. However, the commonly used Euclidean distance is no longer an accurate metric for $L2$-normalized embedding space, i.e., a hyper-sphere. Another challenge of current DDML methods is that their loss functions are usually based on rigid data formats, such as the triplet tuple. Thus, an extra process is needed to prepare data in specific formats. In addition, their losses are obtained from a limited number of samples, which leads to a lack of the global view of the embedding space. In this paper, we replace the Euclidean distance with the cosine similarity to better utilize the $L2$-normalization, which is able to attenuate the curse of dimensionality. More specifically, a novel loss function based on the von Mises-Fisher distribution is proposed to learn a compact hyper-spherical embedding space. Moreover, a new efficient learning algorithm is developed to better capture the global structure of the embedding space. Experiments for both classification and retrieval tasks on several standard datasets show that our method achieves state-of-the-art performance with a simpler training procedure. Furthermore, we demonstrate that, even with a small number of convolutional layers, our model can still obtain significantly better classification performance than the widely used softmax loss.

##### Abstract (translated by Google)
深度距离度量学习（DDML）是基于卷积神经网络以端到端方式学习图像相似性度量的方法，在许多计算机视觉任务中取得了令人鼓舞的结果。嵌入空间中的$ L2 $正规化已被用于改进几种DDML方法的性能。然而，常用的欧几里德距离不再是用于$ L2 $正规化的嵌入空间（即超球）的精确度量。当前DDML方法的另一个挑战是它们的损失函数通常基于刚性数据格式，例如三元组元组。因此，需要额外的过程来准备特定格式的数据。此外，他们的损失是从有限数量的样本中获得的，这导致缺乏对嵌入空间的全局观点。在本文中，我们用余弦相似度代替欧几里得距离，以更好地利用$ L2 $  - 归一化，这能够减少维度的诅咒。更具体地说，提出了一种基于von Mises-Fisher分布的新型损失函数来学习一个紧凑的超球形嵌入空间。此外，开发了一种新的高效学习算法，以更好地捕捉嵌入空间的全局结构。对几个标准数据集进行分类和检索任务的实验表明，我们的方法通过更简单的训练过程实现了最先进的性能。此外，我们证明即使有少量的卷积层，我们的模型仍然可以获得比广泛使用的softmax损失更好的分类性能。

##### URL
[https://arxiv.org/abs/1802.09662](https://arxiv.org/abs/1802.09662)

##### PDF
[https://arxiv.org/pdf/1802.09662](https://arxiv.org/pdf/1802.09662)

