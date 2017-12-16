---
layout: post
title: "Representation Learning by Rotating Your Faces"
date: 2017-05-31 15:18:37
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Face Pose_Estimation Represenation_Learning Quantitative Recognition Face_Recognition
author: Luan Tran, Xi Yin, Xiaoming Liu
mathjax: true
---

* content
{:toc}

##### Abstract
The large pose discrepancy between two face images is one of the fundamental challenges in automatic face recognition. Conventional approaches to pose-invariant face recognition either perform face frontalization on, or learn a pose-invariant representation from, a non-frontal face image. We argue that it is more desirable to perform both tasks jointly to allow them to leverage each other. To this end, this paper proposes a Disentangled Representation learning-Generative Adversarial Network (DR-GAN) with three distinct novelties. First, the encoder-decoder structure of the generator enables DR-GAN to learn a representation that is both generative and discriminative, which can be used for face image synthesis and pose-invariant face recognition. Second, this representation is explicitly disentangled from other face variations such as pose, through the pose code provided to the decoder and pose estimation in the discriminator. Third, DR-GAN can take one or multiple images as the input, and generate one unified identity representation along with an arbitrary number of synthetic face images. Extensive quantitative and qualitative evaluation on a number of controlled and in-the-wild databases demonstrate the superiority of DR-GAN over the state of the art in both learning representations and rotating large-pose face images.

##### Abstract (translated by Google)
两幅人脸图像之间的大姿态差异是自动​​人脸识别的基本挑战之一。姿态不变人脸识别的传统方法或者对非正面人脸图像执行脸部正面化，或者从非正面人脸图像学习姿态不变的表示。我们认为，共同执行这两项任务让他们互相利用是更可取的。为此，本文提出了一个具有三种截然不同的创新的无纠缠表示学习 - 生成对抗网络（DR-GAN）。首先，生成器的编码器 - 解码器结构使得DR-GAN能够学习生成和鉴别的表示，其可以用于人脸图像合成和姿态不变人脸识别。其次，通过提供给解码器的姿态码和鉴别器中的姿态估计，将这种表示明确地从诸如姿态的其他面部变化中解开。第三，DR-GAN可以将一个或多个图像作为输入，并与任意数量的合成人脸图像一起生成一个统一的身份表示。在大量的受控和野外数据库中进行广泛的定量和定性评估，证明了DR-GAN在学习表示和旋转大姿态脸部图像方面优于现有技术。

##### URL
[https://arxiv.org/abs/1705.11136](https://arxiv.org/abs/1705.11136)

##### PDF
[https://arxiv.org/pdf/1705.11136](https://arxiv.org/pdf/1705.11136)

