---
layout: post
title: "Photorealistic Facial Expression Synthesis by the Conditional Difference Adversarial Autoencoder"
date: 2017-08-30 05:37:58
categories: arXiv_CV
tags: arXiv_CV Adversarial Face Recognition Face_Recognition
author: Yuqian Zhou, Bertram Emil Shi
mathjax: true
---

* content
{:toc}

##### Abstract
Photorealistic facial expression synthesis from single face image can be widely applied to face recognition, data augmentation for emotion recognition or entertainment. This problem is challenging, in part due to a paucity of labeled facial expression data, making it difficult for algorithms to disambiguate changes due to identity and changes due to expression. In this paper, we propose the conditional difference adversarial autoencoder, CDAAE, for facial expression synthesis. The CDAAE takes a facial image of a previously unseen person and generates an image of that human face with a target emotion or facial action unit label. The CDAAE adds a feedforward path to an autoencoder structure connecting low level features at the encoder to features at the corresponding level at the decoder. It handles the problem of disambiguating changes due to identity and changes due to facial expression by learning to generate the difference between low-level features of images of the same person but with different facial expressions. The CDAAE structure can be used to generate novel expressions by combining and interpolating between facial expressions/action units within the training set. Our experimental results demonstrate that the CDAAE can preserve identity information when generating facial expression for unseen subjects more faithfully than previous approaches. This is especially advantageous when training with small databases.

##### Abstract (translated by Google)
从单人脸图像合成的真实感人脸表情可以广泛应用于人脸识别，情感识别或娱乐的数据增强。这个问题是有挑战性的，部分原因是标记的面部表情数据很少，使得算法难以消除因身份造成的变化和由于表达引起的变化。在本文中，我们提出了用于面部表情合成的条件差分对抗自编码器CDAAE。 CDAAE获取先前看不见的人的面部图像，并用目标情绪或面部动作单元标签生成该人脸的图像。 CDAAE为自编码器结构添加了前馈路径，将编码器的低级特征连接到解码器相应级别的特征。它通过学习生成同一个人的图像的低级特征之间的差异，但是用不同的面部表情来处理由于身份和面部表情的变化而消除变化的歧义问题。 CDAAE结构可用于通过在训练集内的面部表情/动作单元之间进行组合和插值来生成新的表达。我们的实验结果表明，CDAAE可以比以前的方法更忠实地生成看不见的对象的面部表情时保存身份信息。在使用小型数据库进行培训时，这是特别有利的

##### URL
[https://arxiv.org/abs/1708.09126](https://arxiv.org/abs/1708.09126)

##### PDF
[https://arxiv.org/pdf/1708.09126](https://arxiv.org/pdf/1708.09126)

