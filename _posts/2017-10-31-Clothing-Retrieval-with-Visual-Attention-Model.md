---
layout: post
title: "Clothing Retrieval with Visual Attention Model"
date: 2017-10-31 13:14:59
categories: arXiv_CV
tags: arXiv_CV Attention CNN Detection
author: Zhonghao Wang, Yujun Gu, Ya Zhang, Jun Zhou, Xiao Gu
mathjax: true
---

* content
{:toc}

##### Abstract
Clothing retrieval is a challenging problem in computer vision. With the advance of Convolutional Neural Networks (CNNs), the accuracy of clothing retrieval has been significantly improved. FashionNet[1], a recent study, proposes to employ a set of artificial features in the form of landmarks for clothing retrieval, which are shown to be helpful for retrieval. However, the landmark detection module is trained with strong supervision which requires considerable efforts to obtain. In this paper, we propose a self-learning Visual Attention Model (VAM) to extract attention maps from clothing images. The VAM is further connected to a global network to form an end-to-end network structure through Impdrop connection which randomly Dropout on the feature maps with the probabilities given by the attention map. Extensive experiments on several widely used benchmark clothing retrieval data sets have demonstrated the promise of the proposed method. We also show that compared to the trivial Product connection, the Impdrop connection makes the network structure more robust when training sets of limited size are used.

##### Abstract (translated by Google)
服装检索是计算机视觉中的一个挑战性问题。随着卷积神经网络（CNNs）的发展，服装检索的准确性有了显着的提高。 FashionNet [1]最近的一项研究提出采用一系列地标形式的人工特征来检索服装，这些特征对于检索是有帮助的。然而，具有里程碑意义的检测模块训练有力的监督，这需要相当大的努力获得。在本文中，我们提出了一个自学习的视觉注意模型（VAM）来从服装图像中提取关注图。 VAM进一步连接到全球网络，通过Impract连接形成一个端到端的网络结构，该连接随着关注映射给出的概率在特征映射上随机丢弃。对几种广泛使用的基准服装检索数据集进行了广泛的实验，证明了所提出方法的前景。我们还展示了与简单的产品连接相比，使用训练有限尺寸的集合时，Impdrop连接使得网络结构更加健壮。

##### URL
[https://arxiv.org/abs/1710.11446](https://arxiv.org/abs/1710.11446)

##### PDF
[https://arxiv.org/pdf/1710.11446](https://arxiv.org/pdf/1710.11446)

