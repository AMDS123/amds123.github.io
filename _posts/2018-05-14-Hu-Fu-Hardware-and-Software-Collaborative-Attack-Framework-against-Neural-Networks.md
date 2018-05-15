---
layout: post
title: "Hu-Fu: Hardware and Software Collaborative Attack Framework against Neural Networks"
date: 2018-05-14 10:15:29
categories: arXiv_CV
tags: arXiv_CV Segmentation Face CNN Image_Classification Classification Deep_Learning Detection Recognition Face_Recognition
author: Wenshuo Li, Jincheng Yu, Xuefei Ning, Pengjun Wang, Qi Wei, Yu Wang, Huazhong Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, Deep Learning (DL), especially Convolutional Neural Network (CNN), develops rapidly and is applied to many tasks, such as image classification, face recognition, image segmentation, and human detection. Due to its superior performance, DL-based models have a wide range of application in many areas, some of which are extremely safety-critical, e.g. intelligent surveillance and autonomous driving. Due to the latency and privacy problem of cloud computing, embedded accelerators are popular in these safety-critical areas. However, the robustness of the embedded DL system might be harmed by inserting hardware/software Trojans into the accelerator and the neural network model, since the accelerator and deploy tool (or neural network model) are usually provided by third-party companies. Fortunately, inserting hardware Trojans can only achieve inflexible attack, which means that hardware Trojans can easily break down the whole system or exchange two outputs, but can't make CNN recognize unknown pictures as targets. Though inserting software Trojans has more freedom of attack, it often requires tampering input images, which is not easy for attackers. So, in this paper, we propose a hardware-software collaborative attack framework to inject hidden neural network Trojans, which works as a back-door without requiring manipulating input images and is flexible for different scenarios. We test our attack framework for image classification and face recognition tasks, and get attack success rate of 92.6% and 100% on CIFAR10 and YouTube Faces, respectively, while keeping almost the same accuracy as the unattacked model in the normal mode. In addition, we show a specific attack scenario in which a face recognition system is attacked and gives a specific wrong answer.

##### Abstract (translated by Google)
最近，深度学习（DL）特别是卷积神经网络（CNN）发展迅速，并被应用于许多任务，如图像分类，人脸识别，图像分割和人体检测。由于其优越的性能，基于DL的模型在许多领域具有广泛的应用，其中一些对安全极其重要，例如，智能监控和自动驾驶。由于云计算的延迟和隐私问题，嵌入式加速器在这些安全关键领域非常流行。然而，由于加速器和部署工具（或神经网络模型）通常由第三方公司提供，嵌入式DL系统的健壮性可能因将硬件/软件木马插入加速器和神经网络模型而受到损害。幸运的是，插入硬件木马只能实现不灵活的攻击，这意味着硬件木马可以很容易地分解整个系统或交换两个输出，但不能使CNN将未知图片识别为目标。虽然插入软件木马有更多的攻击自由，但它通常需要篡改输入图像，这对攻击者来说并不容易。因此，在本文中，我们提出了一个硬件 - 软件协作攻击框架来注入隐藏的神经网络木马，它可以作为后门而不需要操纵输入图像，并且对于不同的场景是灵活的。我们测试了我们的图像分类和人脸识别任务的攻击框架，并且在CIFAR10和YouTube Faces上分别获得了92.6％和100％的攻击成功率，同时保持与正常模式下未攻击模型几乎相同的准确性。另外，我们展示了一个特定的攻击场景，其中人脸识别系统受到攻击并给出了特定的错误答案。

##### URL
[https://arxiv.org/abs/1805.05098](https://arxiv.org/abs/1805.05098)

##### PDF
[https://arxiv.org/pdf/1805.05098](https://arxiv.org/pdf/1805.05098)

