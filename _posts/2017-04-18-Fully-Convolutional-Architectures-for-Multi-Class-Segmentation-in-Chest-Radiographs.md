---
layout: post
title: "Fully Convolutional Architectures for Multi-Class Segmentation in Chest Radiographs"
date: 2017-04-18 13:02:51
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN CNN Image_Classification Classification Recognition
author: Alexey A. Novikov, Dimitrios Lenis, David Major, Jiri Hladůvka, Maria Wimmer, Katja Bühler
mathjax: true
---

* content
{:toc}

##### Abstract
The success of deep convolutional neural networks on image classification and recognition tasks has led to new applications in very diversified contexts, including the field of medical imaging. In this paper we investigate and propose neural network architectures within the context of automated segmentation of anatomical organs in chest radiographs, namely for lungs, clavicles and heart. The problem of relative intrinsic imbalances in the dataspace is solved by relating prior class data distributions to the loss function. We investigate three different models and propose the best performing one based on the evaluation results. The models are trained and tested on the publicly available JSRT database, consisting of 247 X-ray images the ground truth masks for which are available in the SCR database. The networks have been trained in a multi-class setup with three target classes. Our best performing model, trained with the loss function based on the Dice coefficient, reached mean Jaccard overlap scores of 95.0\% for lungs, 86.8\% for clavicles and 88.2\% for heart in the multi-class configuration. Though we proceed in a multi-class configuration, our best network reached competitive results on lung segmentation and outperformed single-class state-of-the-art methods on clavicles and heart segmentation tasks.

##### Abstract (translated by Google)
深度卷积神经网络在图像分类识别任务上的成功，带来了在医学影像领域等多元化背景下的新应用。在本文中，我们调查并提出神经网络体系结构的自动分割胸部X光片，即肺，锁骨和心脏的解剖器官。数据空间中相对固有的不平衡问题通过将先前的类数据分布与损失函数相关联来解决。我们调查了三种不同的模型，并根据评估结果提出了最好的模型。这些模型在公开可用的JSRT数据库上进行了训练和测试，包括247张X射线图像，在SCR数据库中提供了地面实况模板。这些网络已经接受了三个目标类别的多级训练。我们表现​​最好的模型，基于Dice系数的损失函数进行训练，在多级构型中，肺部的平均Jaccard重叠分数为95.0％，锁骨为86.8％，心脏为88.2％。虽然我们进行了多级配置，但我们最好的网络在肺部分割方面取得了有竞争力的结果，并且在锁骨和心脏分割任务上超越了单级最先进的方法。

##### URL
[https://arxiv.org/abs/1701.08816](https://arxiv.org/abs/1701.08816)

##### PDF
[https://arxiv.org/pdf/1701.08816](https://arxiv.org/pdf/1701.08816)

