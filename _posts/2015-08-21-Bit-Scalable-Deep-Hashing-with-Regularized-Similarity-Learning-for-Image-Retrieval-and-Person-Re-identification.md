---
layout: post
title: "Bit-Scalable Deep Hashing with Regularized Similarity Learning for Image Retrieval and Person Re-identification"
date: 2015-08-21 06:02:54
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Regularization Re-identification GAN Person_Re-identification CNN
author: Ruimao Zhang, Liang Lin, Rui Zhang, Wangmeng Zuo, Lei Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Extracting informative image features and learning effective approximate hashing functions are two crucial steps in image retrieval . Conventional methods often study these two steps separately, e.g., learning hash functions from a predefined hand-crafted feature space. Meanwhile, the bit lengths of output hashing codes are preset in most previous methods, neglecting the significance level of different bits and restricting their practical flexibility. To address these issues, we propose a supervised learning framework to generate compact and bit-scalable hashing codes directly from raw images. We pose hashing learning as a problem of regularized similarity learning. Specifically, we organize the training images into a batch of triplet samples, each sample containing two images with the same label and one with a different label. With these triplet samples, we maximize the margin between matched pairs and mismatched pairs in the Hamming space. In addition, a regularization term is introduced to enforce the adjacency consistency, i.e., images of similar appearances should have similar codes. The deep convolutional neural network is utilized to train the model in an end-to-end fashion, where discriminative image features and hash functions are simultaneously optimized. Furthermore, each bit of our hashing codes is unequally weighted so that we can manipulate the code lengths by truncating the insignificant bits. Our framework outperforms state-of-the-arts on public benchmarks of similar image search and also achieves promising results in the application of person re-identification in surveillance. It is also shown that the generated bit-scalable hashing codes well preserve the discriminative powers with shorter code lengths.

##### Abstract (translated by Google)
提取信息丰富的图像特征和学习有效的近似散列函数是图像检索的两个关键步骤。常规方法经常分别研究这两个步骤，例如，从预定义的手工制作的特征空间学习散列函数。同时，大多数以前的方法都预设了输出哈希码的比特长度，忽略了不同比特的显着性水平，限制了其实际的灵活性。为了解决这些问题，我们提出了一个监督学习框架，直接从原始图像生成紧凑和可扩展的哈希代码。我们将哈希学习作为正则化相似学习的一个问题。具体而言，我们将训练图像组织成一批三重样本，每个样本包含两个具有相同标签的图像和一个具有不同标签的图像。使用这些三重样本，我们可以最大化匹配对和海明空间中不匹配对之间的余量。此外，引入正则化术语来强化邻接一致性，即类似外观的图像应该具有相似的编码。利用深度卷积神经网络以端到端的方式对模型进行训练，同时优化辨别图像特征和散列函数。而且，我们的哈希码的每一位都是不相同的权重，所以我们可以通过截去无关位来处理代码长度。我们的框架在相似图像搜索的公共基准方面优于现有技术，并且在人员重新识别在监视中的应用方面也取得了可喜的成果。还显示了所生成的比特可扩展哈希码很好地保留了较短代码长度的判别能力。

##### URL
[https://arxiv.org/abs/1508.04535](https://arxiv.org/abs/1508.04535)

##### PDF
[https://arxiv.org/pdf/1508.04535](https://arxiv.org/pdf/1508.04535)

