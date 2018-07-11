---
layout: post
title: "High Fidelity Semantic Shape Completion for Point Clouds using Latent Optimization"
date: 2018-07-09 22:24:17
categories: arXiv_CV
tags: arXiv_CV GAN Embedding Optimization
author: Swaminathan Gurumurthy, Shubham Agrawal
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic shape completion is a challenging problem in 3D computer vision where the task is to generate a complete 3D shape using a partial 3D shape as input. We propose a learning-based approach to complete incomplete 3D shapes through generative modeling and latent manifold optimization. Our algorithm works directly on point clouds. We use an autoencoder and a GAN to learn a distribution of embeddings for point clouds of object classes. An input point cloud with missing regions is first encoded to a feature vector. The representations learnt by the GAN are then used to find the best latent vector on the manifold using a combined optimization that finds a vector in the manifold of plausible vectors that is close to the original input (both in the feature space and the output space of the decoder). Experiments show that our algorithm is capable of successfully reconstructing point clouds with large missing regions with very high fidelity without having to rely on exemplar based database retrieval.

##### Abstract (translated by Google)
语义形状完成是3D计算机视觉中的挑战性问题，其中任务是使用部分3D形状作为输入来生成完整的3D形状。我们提出了一种基于学习的方法，通过生成建模和潜在流形优化来完成不完整的3D形状。我们的算法直接在点云上工作。我们使用自动编码器和GAN来学习对象类点云的嵌入分布。首先将具有缺失区域的输入点云编码为特征向量。然后使用GAN学习的表示来使用组合优化在流形上找到最佳潜在向量，该组合优化在接近原始输入的合理向量的流形中找到向量（在特征空间和输出空间中）解码器）。实验表明，我们的算法能够成功地重建具有高保真度的大缺失区域的点云，而不必依赖基于样本的数据库检索。

##### URL
[http://arxiv.org/abs/1807.03407](http://arxiv.org/abs/1807.03407)

##### PDF
[http://arxiv.org/pdf/1807.03407](http://arxiv.org/pdf/1807.03407)

