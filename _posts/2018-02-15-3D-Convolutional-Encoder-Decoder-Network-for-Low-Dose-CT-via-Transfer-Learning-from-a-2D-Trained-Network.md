---
layout: post
title: "3D Convolutional Encoder-Decoder Network for Low-Dose CT via Transfer Learning from a 2D Trained Network"
date: 2018-02-15 16:51:16
categories: arXiv_CV
tags: arXiv_CV Adversarial Attention GAN CNN Transfer_Learning
author: Hongming Shan, Yi Zhang, Qingsong Yang, Uwe Kruger, Wenxiang Cong, Ge Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Low-dose computed tomography (CT) has attracted a major attention in the medical imaging field, since CT-associated x-ray radiation carries health risks for patients. The reduction of CT radiation dose, however, compromises the signal-to-noise ratio, and may compromise the image quality and the diagnostic performance. Recently, deep-learning-based algorithms have achieved promising results in low-dose CT denoising, especially convolutional neural network (CNN) and generative adversarial network (GAN). This article introduces a Contracting Path-based Convolutional Encoder-decoder (CPCE) network in 2D and 3D configurations within the GAN framework for low-dose CT denoising. A novel feature of our approach is that an initial 3D CPCE denoising model can be directly obtained by extending a trained 2D CNN and then fine-tuned to incorporate 3D spatial information from adjacent slices. Based on the transfer learning from 2D to 3D, the 3D network converges faster and achieves a better denoising performance than that trained from scratch. By comparing the CPCE with recently published methods based on the simulated Mayo dataset and the real MGH dataset, we demonstrate that the 3D CPCE denoising model has a better performance, suppressing image noise and preserving subtle structures.

##### Abstract (translated by Google)
低剂量计算机断层扫描（CT）在医学成像领域引起了重大关注，因为CT相关的X射线辐射对患者带来健康风险。但是，CT辐射剂量的减少会影响信噪比，并可能影响图像质量和诊断性能。最近，基于深度学习的算法在低剂量CT去噪，尤其是卷积神经网络（CNN）和生成对抗网络（GAN）方面取得了令人鼓舞的结果。本文介绍了GAN框架内用于低剂量CT去噪的2D和3D配置中的基于合同路径的卷积编码器 - 解码器（CPCE）网络。我们的方法的一个新特征是可以通过扩展训练后的二维CNN直接获得初始3D CPCE去噪模型，然后进行微调以合并来自相邻切片的三维空间信息。基于从2D到3D的传输学习，3D网络比从头开始训练的3D网络更快地收敛并实现更好的去噪性能。通过比较CPCE和基于模拟Mayo数据集和真实MGH数据集的最近公布的方法，我们证明3D CPCE去噪模型具有更好的性能，抑制图像噪声并保留微妙的结构。

##### URL
[https://arxiv.org/abs/1802.05656](https://arxiv.org/abs/1802.05656)

##### PDF
[https://arxiv.org/pdf/1802.05656](https://arxiv.org/pdf/1802.05656)

