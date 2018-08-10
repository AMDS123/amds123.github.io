---
layout: post
title: "Towards Open-Set Identity Preserving Face Synthesis"
date: 2018-08-09 06:55:19
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
我们提出了一个基于生成对抗网络的框架来解开面部的身份和属性，这样我们可以方便地重新组合不同的身份和属性，以保持开放域中的身份保持面部合成。先前的身份保持面部合成过程主要局限于合成具有已经在训练数据集中的已知身份的面部。为了在训练数据集之外合成具有身份的面部，我们的框架需要该主题的一个输入图像以产生身份矢量，并且任何其他输入面部图像以提取属性矢量捕获，例如姿势，情感，照明，甚至是背景。然后，我们重新组合身份向量和属性向量，以用提取的属性合成主题的新面部。我们提出的框架不需要以任何方式注释面部的属性。它具有不对称损失功能，可以更好地保持身份并稳定训练过程。它还可以有效地利用大量未标记的训练面部图像，以进一步提高未在标记的训练面部数据集中呈现的对象的合成面部的保真度。我们的实验证明了所提出的框架的功效。我们还在更广泛的应用程序中展示了它的用法，包括面部正面化，面部属性变形和面部对抗示例检测。

##### URL
[http://arxiv.org/abs/1803.11182](http://arxiv.org/abs/1803.11182)

##### PDF
[http://arxiv.org/pdf/1803.11182](http://arxiv.org/pdf/1803.11182)

