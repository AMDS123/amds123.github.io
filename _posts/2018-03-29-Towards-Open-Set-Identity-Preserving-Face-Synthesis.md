---
layout: post
title: "Towards Open-Set Identity Preserving Face Synthesis"
date: 2018-03-29 17:54:51
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Face Detection
author: Jianmin Bao, Dong Chen, Fang Wen, Houqiang Li, Gang Hua
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a framework based on Generative Adversarial Networks to disentangle the identity and attributes of faces, such that we can conveniently recombine different identities and attributes for identity preserving face synthesis in open domains. Previous identity preserving face synthesis processes are largely confined to synthesizing faces with known identities that are already in the training dataset. To synthesize a face with identity outside the training dataset, our framework requires one input image of that subject to produce an identity vector, and any other input face image to extract an attribute vector capturing, e.g., pose, emotion, illumination, and even the background. We then recombine the identity vector and the attribute vector to synthesize a new face of the subject with the extracted attribute. Our proposed framework does not need to annotate the attributes of faces in any way. It is trained with an asymmetric loss function to better preserve the identity and stabilize the training process. It can also effectively leverage large amounts of unlabeled training face images to further improve the fidelity of the synthesized faces for subjects that are not presented in the labeled training face dataset. Our experiments demonstrate the efficacy of the proposed framework. We also present its usage in a much broader set of applications including face frontalization, face attribute morphing, and face adversarial example detection.

##### Abstract (translated by Google)
我们提出了一个基于生成敌对网络的框架来解开人脸的身份和属性，这样我们可以方便地重组不同的身份和属性，以便在开放域中保留人脸合成。以前的身份保持人脸合成过程主要局限于合成已知身份的人脸，这些身份已经存在于训练数据集中。为了在训练数据集外合成具有身份的面部，我们的框架需要该主体的一个输入图像产生身份向量，并且需要任何其他输入面部图像以提取属性向量捕捉，例如姿势，情绪，照明，甚至是背景。然后，我们重新组合身份向量和属性向量来合成提取属性的主体的新面部。我们提出的框架不需要以任何方式注释面部的属性。它受到不对称损失函数的训练，以更好地保持身份并稳定训练过程。它还可以有效地利用大量未标记的训练脸部图像来进一步提高未标注的训练脸部数据集中呈现的对象的合成脸部的逼真度。我们的实验证明了所提议的框架的功效。我们还将其用法应用在更广泛的应用程序中，包括人脸正面化，人脸属性变形和人脸对抗示例检测。

##### URL
[http://arxiv.org/abs/1803.11182](http://arxiv.org/abs/1803.11182)

##### PDF
[http://arxiv.org/pdf/1803.11182](http://arxiv.org/pdf/1803.11182)

