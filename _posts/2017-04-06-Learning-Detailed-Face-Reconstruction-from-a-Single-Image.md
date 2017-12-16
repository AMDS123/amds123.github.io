---
layout: post
title: "Learning Detailed Face Reconstruction from a Single Image"
date: 2017-04-06 15:05:16
categories: arXiv_CV
tags: arXiv_CV Face CNN Quantitative Detection Recognition
author: Elad Richardson, Matan Sela, Roy Or-El, Ron Kimmel
mathjax: true
---

* content
{:toc}

##### Abstract
Reconstructing the detailed geometric structure of a face from a given image is a key to many computer vision and graphics applications, such as motion capture and reenactment. The reconstruction task is challenging as human faces vary extensively when considering expressions, poses, textures, and intrinsic geometries. While many approaches tackle this complexity by using additional data to reconstruct the face of a single subject, extracting facial surface from a single image remains a difficult problem. As a result, single-image based methods can usually provide only a rough estimate of the facial geometry. In contrast, we propose to leverage the power of convolutional neural networks to produce a highly detailed face reconstruction from a single image. For this purpose, we introduce an end-to-end CNN framework which derives the shape in a coarse-to-fine fashion. The proposed architecture is composed of two main blocks, a network that recovers the coarse facial geometry (CoarseNet), followed by a CNN that refines the facial features of that geometry (FineNet). The proposed networks are connected by a novel layer which renders a depth image given a mesh in 3D. Unlike object recognition and detection problems, there are no suitable datasets for training CNNs to perform face geometry reconstruction. Therefore, our training regime begins with a supervised phase, based on synthetic images, followed by an unsupervised phase that uses only unconstrained facial images. The accuracy and robustness of the proposed model is demonstrated by both qualitative and quantitative evaluation tests.

##### Abstract (translated by Google)
从给定的图像重建人脸的详细几何结构是许多计算机视觉和图形应用程序（如动作捕捉和重现）的关键。重建任务是具有挑战性的，因为当考虑表情，姿势，纹理和内在几何形状时，人脸会变化很大。虽然许多方法通过使用附加数据来重建单个对象的面部来解决这种复杂性，但从单个图像提取面部表面仍然是一个难题。因此，基于单幅图​​像的方法通常只能提供对面部几何图形的粗略估计。相比之下，我们建议利用卷积神经网络的功能从单一的图像产生一个高度详细的脸部重建。为此，我们引入一个端到端的CNN框架，以粗到细的方式导出形状。所提出的体系结构由两个主要部分组成，一个网络可以恢复粗糙的面部几何（CoarseNet），然后是一个细化该几何体（FineNet）的面部特征的CNN。所提出的网络通过新颖的层连接，该层在3D中给出深度图像。与物体识别和检测问题不同，没有合适的数据集来训练CNN来执行脸部几何重建。因此，我们的训练制度开始于基于合成图像的监督阶段，随后是仅使用无约束面部图像的无监督阶段。定性和定量评估测试证明了所建模型的准确性和鲁棒性。

##### URL
[https://arxiv.org/abs/1611.05053](https://arxiv.org/abs/1611.05053)

##### PDF
[https://arxiv.org/pdf/1611.05053](https://arxiv.org/pdf/1611.05053)

