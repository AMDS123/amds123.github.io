---
layout: post
title: "The Automatic Identification of Butterfly Species"
date: 2018-03-18 08:47:20
categories: arXiv_CV
tags: arXiv_CV Deep_Learning Prediction Detection Recognition
author: Juanying Xie, Qi Hou, Yinghuan Shi, Lv Peng, Liping Jing, Fuzhen Zhuang, Junping Zhang, Xiaoyang Tang, Shengquan Xu
mathjax: true
---

* content
{:toc}

##### Abstract
The available butterfly data sets comprise a few limited species, and the images in the data sets are always standard patterns without the images of butterflies in their living environment. To overcome the aforementioned limitations in the butterfly data sets, we build a butterfly data set composed of all species of butterflies in China with 4270 standard pattern images of 1176 butterfly species, and 1425 images from living environment of 111 species. We propose to use the deep learning technique Faster-Rcnn to train an automatic butterfly identification system including butterfly position detection and species recognition. We delete those species with only one living environment image from data set, then partition the rest images from living environment into two subsets, one used as test subset, the other as training subset respectively combined with all standard pattern butterfly images or the standard pattern butterfly images with the same species of the images from living environment. In order to construct the training subset for FasterRcnn, nine methods were adopted to amplifying the images in the training subset including the turning of up and down, and left and right, rotation with different angles, adding noises, blurring, and contrast ratio adjusting etc. Three prediction models were trained. The mAP (Mean Average prediction) criterion was used to evaluate the performance of the prediction model. The experimental results demonstrate that our Faster-Rcnn based butterfly automatic identification system performed well, and its worst mAP is up to 60%, and can simultaneously detect the positions of more than one butterflies in one images from living environment and recognize the species of those butterflies as well.

##### Abstract (translated by Google)
可用的蝴蝶数据集包括一些有限的种类，并且数据集中的图像总是标准模式，没有生活环境中的蝴蝶图像。为了克服上述蝶形数据集的局限性，我们构建了由中国所有蝴蝶种类组成的蝴蝶数据集，共有1176种蝴蝶物种的4270个标准图案图像和111种物种生活环境中的1425个图像。我们建议使用深度学习技术Faster-Rcnn来训练包括蝶形位置检测和物种识别在内的自动蝶形识别系统。我们从数据集中删除那些只有一幅居住环境图像的物种，然后将剩余的图像从生活环境中分割成两个子集，一个用作测试子集，另一个作为训练子集分别与所有标准模式蝴蝶图像或标准模式蝴蝶图像具有来自生活环境的相同种类的图像。为了构建FasterRcnn的训练子集，我们采用了九种方法来放大训练子集中的图像，包括上下左右旋转，不同角度旋转，增加噪声，模糊和对比度调整等。三种预测模型均经过训练。使用mAP（平均平均预测）标准来评估预测模型的性能。实验结果表明，我们基于Faster-Rcnn的蝶形自动识别系统表现良好，其最差的mAP达到60％，并且能够同时检测生活环境中一幅图像中多个蝴蝶的位置，并识别出这些蝴蝶的种类蝴蝶也是如此。

##### URL
[https://arxiv.org/abs/1803.06626](https://arxiv.org/abs/1803.06626)

##### PDF
[https://arxiv.org/pdf/1803.06626](https://arxiv.org/pdf/1803.06626)

