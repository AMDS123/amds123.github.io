---
layout: post
title: "3D Convolutional Neural Networks for Tumor Segmentation using Long-range 2D Context"
date: 2018-07-23 13:31:51
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN CNN Deep_Learning Recognition
author: Pawel Mlynarski, Herv&#xe9; Delingette, Antonio Criminisi, Nicholas Ayache
mathjax: true
---

* content
{:toc}

##### Abstract
We present an efficient deep learning approach for the challenging task of tumor segmentation in multisequence MR images. In recent years, Convolutional Neural Networks (CNN) have achieved state-of-the-art performances in a large variety of recognition tasks in medical imaging. Because of the considerable computational cost of CNNs, large volumes such as MRI are typically processed by subvolumes, for instance slices (axial, coronal, sagittal) or small 3D patches. In this paper we introduce a CNN-based model which efficiently combines the advantages of the short-range 3D context and the long-range 2D context. To overcome the limitations of specific choices of neural network architectures, we also propose to merge outputs of several cascaded 2D-3D models by a voxelwise voting strategy. Furthermore, we propose a network architecture in which the different MR sequences are processed by separate subnetworks in order to be more robust to the problem of missing MR sequences. Finally, a simple and efficient algorithm for training large CNN models is introduced. We evaluate our method on the public benchmark of the BRATS 2017 challenge on the task of multiclass segmentation of malignant brain tumors. Our method achieves good performances and produces accurate segmentations with median Dice scores of 0.918 (whole tumor), 0.883 (tumor core) and 0.854 (enhancing core). Our approach can be naturally applied to various tasks involving segmentation of lesions or organs.

##### Abstract (translated by Google)
我们提出了一种有效的深度学习方法，用于多序列MR图像中肿瘤分割的挑战性任务。近年来，卷积神经网络（CNN）已经在医学成像中的各种识别任务中实现了最先进的性能。由于CNN的相当大的计算成本，诸如MRI的大体积通常由子体积处理，例如切片（轴向，冠状，矢状）或小的3D贴片。在本文中，我们介绍了一种基于CNN的模型，该模型有效地结合了短距离3D上下文和远程2D上下文的优点。为了克服神经网络架构特定选择的局限性，我们还建议通过体素投票策略合并几个级联2D-3D模型的输出。此外，我们提出了一种网络体系结构，其中不同的MR序列由单独的子网络处理，以便更加鲁棒地解决丢失MR序列的问题。最后，介绍了一种简单有效的训练大型CNN模型的算法。我们在BRATS 2017挑战的公共基准上评估了我们对恶性脑肿瘤多类分割任务的方法。我们的方法取得了良好的性能并产生准确的分割，中位Dice评分为0.918（整个肿瘤），0.883（肿瘤核心）和0.854（增强核心）。我们的方法可以自然地应用于涉及病变或器官分割的各种任务。

##### URL
[http://arxiv.org/abs/1807.08599](http://arxiv.org/abs/1807.08599)

##### PDF
[http://arxiv.org/pdf/1807.08599](http://arxiv.org/pdf/1807.08599)

