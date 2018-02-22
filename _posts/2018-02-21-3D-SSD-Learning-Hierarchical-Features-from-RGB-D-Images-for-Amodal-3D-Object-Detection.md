---
layout: post
title: "3D-SSD: Learning Hierarchical Features from RGB-D Images for Amodal 3D Object Detection"
date: 2018-02-21 09:06:33
categories: arXiv_CV
tags: arXiv_CV Object_Detection Prediction Detection
author: Qianhui Luo, Huifang Ma, Yue Wang, Li Tang, Rong Xiong
mathjax: true
---

* content
{:toc}

##### Abstract
This paper aims at developing a faster and a more accurate solution to the amodal 3D object detection problem for indoor scenes. It is achieved through a novel neural network that takes a pair of RGB-D images as the input and delivers oriented 3D bounding boxes as the output. The network, named 3D-SSD, composed of two parts: hierarchical feature fusion and multi-layer prediction. The hierarchical feature fusion combines appearance and geometric features from RGB-D images while the multi-layer prediction utilizes multi-scale features for object detection. As a result, the network can exploit 2.5D representations in a synergetic way to improve the accuracy and efficiency. The issue of object sizes is addressed by attaching a set of 3D anchor boxes with varying sizes to every location of the prediction layers. At the end stage, the category scores for 3D anchor boxes are generated with adjusted positions, sizes and orientations respectively, leading to the final detections using non-maximum suppression. In the training phase, the positive samples are identified with the aid of 2D ground truth to avoid the noisy estimation of depth from raw data, which guide to a better converged model. Experiments performed on the challenging SUN RGB-D dataset show that our algorithm outperforms the state-of-the-art Deep Sliding Shape by 10.2% mAP and 88x faster. Further, experiments also suggest our approach achieves comparable accuracy and is 386x faster than the state-of-art method on the NYUv2 dataset even with a smaller input image size.

##### Abstract (translated by Google)
本文旨在为室内场景的节理三维物体检测问题开发更快，更准确的解决方案。它是通过一个新的神经网络实现的，它将一对RGB-D图像作为输入，并提供面向3D的边界框作为输出。这个名为3D-SSD的网络由两部分组成：分层特征融合和多层预测。分层特征融合结合了RGB-D图像的外观和几何特征，而多层预测利用多尺度特征进行物体检测。因此，网络可以以协同方式利用2.5D表示来提高准确性和效率。对象大小的问题通过将一组具有变化大小的3D锚箱附加到预测层的每个位置来解决。在最后阶段，通过分别调整位置，大小和方向来生成3D锚箱的类别分数，从而导致使用非最大抑制的最终检测。在训练阶段，利用2D地面真值识别阳性样本，以避免对原始数据进行深度噪声估计，从而指导更好的融合模型。在具有挑战性的SUN RGB-D数据集上进行的实验表明，我们的算法比现有技术的Deep Sliding Shape的性能提高了10.2％，速度提高了88倍。此外，实验还表明，我们的方法达到了相当的准确性，即使输入图像尺寸较小，也比NYUv2数据集的现有技术快了386倍。

##### URL
[http://arxiv.org/abs/1711.00238](http://arxiv.org/abs/1711.00238)

##### PDF
[http://arxiv.org/pdf/1711.00238](http://arxiv.org/pdf/1711.00238)

