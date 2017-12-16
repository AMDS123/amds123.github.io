---
layout: post
title: "Binary Generative Adversarial Networks for Image Retrieval"
date: 2017-08-08 14:02:40
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Adversarial GAN
author: Jingkuan Song
mathjax: true
---

* content
{:toc}

##### Abstract
The most striking successes in image retrieval using deep hashing have mostly involved discriminative models, which require labels. In this paper, we use binary generative adversarial networks (BGAN) to embed images to binary codes in an unsupervised way. By restricting the input noise variable of generative adversarial networks (GAN) to be binary and conditioned on the features of each input image, BGAN can simultaneously learn a binary representation per image, and generate an image plausibly similar to the original one. In the proposed framework, we address two main problems: 1) how to directly generate binary codes without relaxation? 2) how to equip the binary representation with the ability of accurate image retrieval? We resolve these problems by proposing new sign-activation strategy and a loss function steering the learning process, which consists of new models for adversarial loss, a content loss, and a neighborhood structure loss. Experimental results on standard datasets (CIFAR-10, NUSWIDE, and Flickr) demonstrate that our BGAN significantly outperforms existing hashing methods by up to 107\% in terms of~mAP (See Table tab.res.map.comp) Our anonymous code is available at: this https URL

##### Abstract (translated by Google)
使用深度哈希的图像检索中最引人注目的成功主要涉及需要标签的区分模型。在本文中，我们使用二元生成对抗网络（BGAN）以无监督的方式将图像嵌入二进制代码。通过将生成对抗网络（GAN）的输入噪声变量限制为二进制，并且以每个输入图像的特征为条件，BGAN可以同时学习每个图像的二进制表示，并生成与原始图像振铃相似的图像。在提出的框架中，我们解决了两个主要问题：1）如何直接生成没有放松的二进制码？ 2）如何使二进制表示具有准确的图像检索能力？我们通过提出新的签名激活策略和损失函数来解决这些问题，其中学习过程由对抗性损失，内容损失和邻里结构损失的新模型组成。在标准数据集（CIFAR-10，NUSWIDE和Flickr）上的实验结果表明，我们的BGAN在〜mAP方面明显优于现有的散列方法（参见Table tab.res.map.comp），高达107％。我们的匿名代码是可在此https网址获得

##### URL
[https://arxiv.org/abs/1708.04150](https://arxiv.org/abs/1708.04150)

##### PDF
[https://arxiv.org/pdf/1708.04150](https://arxiv.org/pdf/1708.04150)

