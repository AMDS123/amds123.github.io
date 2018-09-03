---
layout: post
title: "Learning Data Augmentation for Brain Tumor Segmentation with Coarse-to-Fine Generative Adversarial Networks"
date: 2018-08-31 07:15:12
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation GAN
author: Tony C.W Mok, Albert C.S Chung
mathjax: true
---

* content
{:toc}

##### Abstract
There is a common belief that the successful training of deep neural networks requires many annotated training samples, which are often expensive and difficult to obtain especially in the biomedical imaging field. While it is often easy for researchers to use data augmentation to expand the size of training sets, constructing and generating generic augmented data that is able to teach the network the desired invariance and robustness properties using traditional data augmentation techniques is challenging in practice. In this paper, we propose a novel automatic data augmentation method that uses generative adversarial networks to learn augmentations that enable machine learning based method to learn the available annotated samples more efficiently. The architecture consists of a coarse-to-fine generator to capture the manifold of the training sets and generate generic augmented data. In our experiments, we show the efficacy of our approach on a Magnetic Resonance Imaging (MRI) image, achieving improvements of 3.5% Dice coefficient on the BRATS15 Challenge dataset as compared to traditional augmentation approaches. Also, our proposed method successfully boosts a common segmentation network to reach the state-of-the-art performance on the BRATS15 Challenge.

##### Abstract (translated by Google)
人们普遍认为，深度神经网络的成功训练需要许多带注释的训练样本，这些样本通常很昂贵且难以获得，特别是在生物医学成像领域。虽然研究人员通常很容易使用数据增加来扩展训练集的大小，但是构建和生成能够使用传统数据增强技术教授网络所需的不变性和鲁棒性属性的通用增强数据在实践中具有挑战性。在本文中，我们提出了一种新颖的自动数据增强方法，该方法使用生成对抗网络来学习增强，使基于机器学习的方法能够更有效地学习可用的注释样本。该体系结构由粗到精生成器组成，用于捕获训练集的多样性并生成通用的增强数据。在我们的实验中，我们展示了我们的方法在磁共振成像（MRI）图像上的功效，与传统的增强方法相比，在BRATS15 Challenge数据集上实现了3.5％Dice系数的改进。此外，我们提出的方法成功地推动了一个通用的分段网络，以达到BRATS15 Challenge的最先进性能。

##### URL
[http://arxiv.org/abs/1805.11291](http://arxiv.org/abs/1805.11291)

##### PDF
[http://arxiv.org/pdf/1805.11291](http://arxiv.org/pdf/1805.11291)

