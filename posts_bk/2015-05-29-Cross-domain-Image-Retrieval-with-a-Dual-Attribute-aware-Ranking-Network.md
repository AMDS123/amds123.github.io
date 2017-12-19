---
layout: post
title: "Cross-domain Image Retrieval with a Dual Attribute-aware Ranking Network"
date: 2015-05-29 04:46:37
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Review
author: Junshi Huang, Rogerio S. Feris, Qiang Chen, Shuicheng Yan
mathjax: true
---

* content
{:toc}

##### Abstract
We address the problem of cross-domain image retrieval, considering the following practical application: given a user photo depicting a clothing image, our goal is to retrieve the same or attribute-similar clothing items from online shopping stores. This is a challenging problem due to the large discrepancy between online shopping images, usually taken in ideal lighting/pose/background conditions, and user photos captured in uncontrolled conditions. To address this problem, we propose a Dual Attribute-aware Ranking Network (DARN) for retrieval feature learning. More specifically, DARN consists of two sub-networks, one for each domain, whose retrieval feature representations are driven by semantic attribute learning. We show that this attribute-guided learning is a key factor for retrieval accuracy improvement. In addition, to further align with the nature of the retrieval problem, we impose a triplet visual similarity constraint for learning to rank across the two sub-networks. Another contribution of our work is a large-scale dataset which makes the network learning feasible. We exploit customer review websites to crawl a large set of online shopping images and corresponding offline user photos with fine-grained clothing attributes, i.e., around 450,000 online shopping images and about 90,000 exact offline counterpart images of those online ones. All these images are collected from real-world consumer websites reflecting the diversity of the data modality, which makes this dataset unique and rare in the academic community. We extensively evaluate the retrieval performance of networks in different configurations. The top-20 retrieval accuracy is doubled when using the proposed DARN other than the current popular solution using pre-trained CNN features only (0.570 vs. 0.268).

##### Abstract (translated by Google)
考虑到以下实际应用，我们针对跨域图像检索的问题：给出描绘服装图像的用户照片，我们的目标是从网上商店检索相同或属性相似的服装项目。由于在线购物图像（通常在理想的照明/姿势/背景条件下拍摄）和在不受控制的条件下拍摄的用户照片之间的巨大差异，这是一个具有挑战性的问题。为了解决这个问题，我们提出了一个用于检索特征学习的双属性感知排名网络（DARN）。更具体地说，DARN由两个子网络组成，每个子网络一个，其检索特征表示由语义属性学习驱动。我们表明，这种属性引导学习是提高检索准确性的关键因素。此外，为了进一步符合检索问题的性质，我们强加三重视觉相似性约束，学习排序在两个子网络。我们的工作的另一个贡献是使网络学习可行的大规模数据集。我们利用客户浏览网站抓取一大批网上购物图片和相应的离线用户照片，具有细致的服装属性，即约45万个在线购物图像和约9万个在线相应图像。所有这些图像都是从真实世界的消费者网站收集的，反映了数据模式的多样性，这使得这个数据集在学术界是独一无二的。我们广泛评估不同配置的网络的检索性能。除了使用预先训练的CNN特征（0.570 vs. 0.268）的当前流行的解决方案以外，使用所提议的DARN时，前20位检索准确性提高了一倍。

##### URL
[https://arxiv.org/abs/1505.07922](https://arxiv.org/abs/1505.07922)

##### PDF
[https://arxiv.org/pdf/1505.07922](https://arxiv.org/pdf/1505.07922)

