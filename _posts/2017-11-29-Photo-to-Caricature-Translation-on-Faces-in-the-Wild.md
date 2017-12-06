---
layout: post
title: "Photo-to-Caricature Translation on Faces in the Wild"
date: 2017-11-29 09:12:50
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN CNN
author: Ziqiang Zheng, Haiyong Zheng, Zhibin Yu, Zhaorui Gu, Bing Zheng
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, image-to-image translation has been made much progress owing to the success of conditional Generative Adversarial Networks (cGANs). However, it's still very challenging for translation tasks with the requirement of high-level visual information conversion, such as photo-to-caricature translation that requires satire, exaggeration, lifelikeness and artistry. We present an approach for learning to translate faces in the wild from the source photo domain to the target caricature domain with different styles, which can also be used for other high-level image-to-image translation tasks. In order to capture global structure with local statistics while translation, we design a dual pathway model of cGAN with one global discriminator and one patch discriminator. Beyond standard convolution (Conv), we propose a new parallel convolution (ParConv) to construct Parallel Convolutional Neural Networks (ParCNNs) for both global and patch discriminators, which can combine the information from previous layer with the current layer. For generator, we provide three more extra losses in association with adversarial loss to constrain consistency for generated output itself and with the target. Also the style can be controlled by the input style info vector. Experiments on photo-to-caricature translation of faces in the wild show considerable performance gain of our proposed method over state-of-the-art translation methods as well as its potential real applications.

##### Abstract (translated by Google)
最近，由于条件生成对抗网络（cGANs）的成功，图像到图像的翻译已经取得了很大的进展。然而，要求高水平视觉信息转换的翻译任务，如需要讽刺，夸张，逼真，艺术的照片 - 漫画翻译，仍然是一个非常具有挑战性的问题。我们提出了一种学习方法，将来自源照片域的狂野面部以不同风格翻译成目标漫画域，也可以用于其他高级图像到图像的翻译任务。为了在翻译的同时捕捉全局结构和本地统计信息，我们设计了一个具有一个全局鉴别器和一个补码鉴别器的cGAN双路径模型。除了标准卷积（Conv）之外，我们还提出了一种新的并行卷积（ParConv）来构造全局和区块识别器的并行卷积神经网络（ParCNNs），它可以将来自前一层的信息与当前层相结合。对于发电机，我们提供三个与对抗损失相关的额外损失，以限制生成的输出本身和目标的一致性。样式也可以通过输入样式信息向量来控制。野外人脸照片到漫画翻译的实验表明，我们提出的方法在相对于最先进的翻译方法以及其潜在的实际应用方面获得了相当大的性能收益。

##### URL
[https://arxiv.org/abs/1711.10735](https://arxiv.org/abs/1711.10735)

