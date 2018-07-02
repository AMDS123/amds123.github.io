---
layout: post
title: "Asymmetric Similarity Loss Function to Balance Precision and Recall in Highly Unbalanced Deep Medical Image Segmentation"
date: 2018-06-29 16:16:19
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Prediction
author: Seyed Raein Hashemi, Seyed Sadegh Mohseni Salehi, Deniz Erdogmus, Sanjay P. Prabhu, Simon K. Warfield, Ali Gholipour
mathjax: true
---

* content
{:toc}

##### Abstract
Fully convolutional deep neural networks have been asserted to be fast and precise frameworks with great potential in image segmentation. One of the major challenges in utilizing such networks raises when data is unbalanced, which is common in many medical imaging applications such as lesion segmentation where lesion class voxels are often much lower in numbers than non-lesion voxels. A trained network with unbalanced data may make predictions with high precision and low recall, being severely biased towards the non-lesion class which is particularly undesired in medical applications where false negatives are actually more important than false positives. Various methods have been proposed to address this problem including two step training, sample re-weighting, balanced sampling, and similarity loss functions. In this paper we developed a patch-wise 3D densely connected network with an asymmetric loss function, where we used large overlapping image patches for intrinsic and extrinsic data augmentation, a patch selection algorithm, and a patch prediction fusion strategy based on B-spline weighted soft voting to take into account the uncertainty of prediction in patch borders. We applied this method to lesion segmentation based on the MSSEG 2016 and ISBI 2015 challenges, where we achieved average Dice similarity coefficient of 69.9% and 65.74%, respectively. In addition to the proposed loss, we trained our network with focal and generalized Dice loss functions. Significant improvement in $F_1$ and $F_2$ scores and the APR curve was achieved in test using the asymmetric similarity loss layer and our 3D patch prediction fusion. The asymmetric similarity loss based on $F_\beta$ scores generalizes the Dice similarity coefficient and can be effectively used with the patch-wise strategy developed here to train fully convolutional deep neural networks for highly unbalanced image segmentation.

##### Abstract (translated by Google)
完全卷积深度神经网络被认为是图像分割具有巨大潜力的快速精确框架。当数据不平衡时，利用这种网络的主要挑战之一就是提升，这在诸如病变分割的许多医学成像应用中是常见的，其中病变类体素的数量通常远低于非病变体素。训练有素的网络数据不平衡可能导致高精度和低回忆率的预测，严重偏向于非病变类别，这在医学应用中尤为不利，其中假阴性实际上比假阳性更重要。已经提出了各种方法来解决这个问题，包括两步训练，样本重新加权，均衡采样和相似性丢失函数。在本文中，我们开发了一个具有非对称损失函数的拼接三维密集连接网络，其中我们使用大的重叠图像补丁进行内在和外在数据增强，补丁选择算法和基于B样条加权的补丁预测融合策略软投票以考虑补丁边界中预测的不确定性。我们将这种方法应用于基于MSSEG 2016和ISBI 2015挑战的病灶分割，其中我们的平均Dice相似系数分别达到69.9％和65.74％。除了建议的损失之外，我们还利用焦点和广义Dice损失功能训练了我们的网络。在使用非对称相似性丢失层和我们的3D片段预测融合的测试中，$ F_1 $和$ F_2 $得分和APR曲线显着改善。基于$ F_ \ beta $分数的不对称相似性损失概括了Dice相似性系数，并且可以有效地用于此处开发的面片方式策略来训练完全卷积深度神经网络以用于高度不平衡的图像分割。

##### URL
[http://arxiv.org/abs/1803.11078](http://arxiv.org/abs/1803.11078)

##### PDF
[http://arxiv.org/pdf/1803.11078](http://arxiv.org/pdf/1803.11078)

