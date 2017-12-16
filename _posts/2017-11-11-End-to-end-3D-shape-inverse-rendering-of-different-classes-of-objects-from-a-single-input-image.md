---
layout: post
title: "End-to-end 3D shape inverse rendering of different classes of objects from a single input image"
date: 2017-11-11 19:13:57
categories: arXiv_CV
tags: arXiv_CV Face
author: Shima Kamyab, S. Zohreh Azimifar
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper a semi-supervised deep framework is proposed for the problem of 3D shape inverse rendering from a single 2D input image. The main structure of proposed framework consists of unsupervised pre-trained components which significantly reduce the need to labeled data for training the whole framework. using labeled data has the advantage of achieving to accurate results without the need to predefined assumptions about image formation process. Three main components are used in the proposed network: an encoder which maps 2D input image to a representation space, a 3D decoder which decodes a representation to a 3D structure and a mapping component in order to map 2D to 3D representation. The only part that needs label for training is the mapping part with not too many parameters. The other components in the network can be pre-trained unsupervised using only 2D images or 3D data in each case. The way of reconstructing 3D shapes in the decoder component, inspired by the model based methods for 3D reconstruction, maps a low dimensional representation to 3D shape space with the advantage of extracting the basis vectors of shape space from training data itself and is not restricted to a small set of examples as used in predefined models. Therefore, the proposed framework deals directly with coordinate values of the point cloud representation which leads to achieve dense 3D shapes in the output. The experimental results on several benchmark datasets of objects and human faces and comparing with recent similar methods shows the power of proposed network in recovering more details from single 2D images.

##### Abstract (translated by Google)
本文提出了一个半监督的深度框架，从单一的二维输入图像的三维形状逆向渲染问题。所提出的框架的主要结构由无监督的预先训练的组件组成，这显着地减少了用于训练整个框架的标记数据的需要。使用标记的数据具有实现精确结果的优点，而不需要关于图像形成过程的预定义假设。在所提出的网络中使用三个主要组件：将2D输入图像映射到表示空间的编码器，将表示解码为3D结构的3D解码器和映射组件，以便将2D映射到3D表示。唯一需要标注的部分是参数不多的映射部分。网络中的其他组件可以在每种情况下仅使用2D图像或3D数据进行无监督预训练。在基于基于模型的三维重建方法的启发下，在解码器组件中重建三维形状的方式将低维表示映射到三维形状空间，其优点是从训练数据本身提取形状空间的基矢量，并且不限于在预定义模型中使用的一小组示例。因此，所提出的框架直接处理点云表示的坐标值，从而导致在输出中实现密集的3D形状。在对象和人脸的几个基准数据集上的实验结果以及与最近类似的方法进行比较，显示了所提出的网络在从单个2D图像中恢复更多细节的能力。

##### URL
[https://arxiv.org/abs/1711.05858](https://arxiv.org/abs/1711.05858)

##### PDF
[https://arxiv.org/pdf/1711.05858](https://arxiv.org/pdf/1711.05858)

