---
layout: post
title: "UV-GAN: Adversarial Facial UV Map Completion for Pose-invariant Face Recognition"
date: 2017-12-13 10:52:42
categories: arXiv_CV
tags: arXiv_CV Adversarial Sparse GAN Face CNN Recognition Face_Recognition
author: Jiankang Deng, Shiyang Cheng, Niannan Xue, Yuxiang Zhou, Stefanos Zafeiriou
mathjax: true
---

* content
{:toc}

##### Abstract
Recently proposed robust 3D face alignment methods establish either dense or sparse correspondence between a 3D face model and a 2D facial image. The use of these methods presents new challenges as well as opportunities for facial texture analysis. In particular, by sampling the image using the fitted model, a facial UV can be created. Unfortunately, due to self-occlusion, such a UV map is always incomplete. In this paper, we propose a framework for training Deep Convolutional Neural Network (DCNN) to complete the facial UV map extracted from in-the-wild images. To this end, we first gather complete UV maps by fitting a 3D Morphable Model (3DMM) to various multiview image and video datasets, as well as leveraging on a new 3D dataset with over 3,000 identities. Second, we devise a meticulously designed architecture that combines local and global adversarial DCNNs to learn an identity-preserving facial UV completion model. We demonstrate that by attaching the completed UV to the fitted mesh and generating instances of arbitrary poses, we can increase pose variations for training deep face recognition/verification models, and minimise pose discrepancy during testing, which lead to better performance. Experiments on both controlled and in-the-wild UV datasets prove the effectiveness of our adversarial UV completion model. We achieve state-of-the-art verification accuracy, $94.05\%$, under the CFP frontal-profile protocol only by combining pose augmentation during training and pose discrepancy reduction during testing. We will release the first in-the-wild UV dataset (we refer as WildUV) that comprises of complete facial UV maps from 1,892 identities for research purposes.

##### Abstract (translated by Google)
最近提出的鲁棒3D人脸对准方法建立了3D人脸模型和2D人脸图像之间的密集或稀疏对应关系。这些方法的使用给面部纹理分析带来了新的挑战以及机遇。特别是，通过使用拟合模型对图像进行采样，可以创建面部UV。不幸的是，由于自闭症，这样的UV图总是不完整的。在本文中，我们提出了一个训练深度卷积神经网络（DCNN）来完成从野外图像中提取的面部UV地图的框架。为此，我们首先通过将3D形变模型（3DMM）拟合到各种多视图图像和视频数据集以及利用具有超过3000个身份的新的3D数据集来收集完整的UV地图。其次，我们设计了一个精心设计的架构，结合了本地和全球的敌对DCNN来学习保持身份的面部UV完成模型。我们证明了通过将完成的UV附加到拟合的网格并生成任意姿势的实例，我们可以增加训练深度人脸识别/验证模型的姿态变化，并且在测试期间最小化姿势差异，这导致更好的性能。在受控和野外UV数据集上的实验证明了我们的敌对UV完成模型的有效性。在CFP前端协议下，我们只能通过在训练过程中结合姿势增强和在测试中减少姿势差异来实现最新的验证准确性，即$ 94.05 \％$。我们将发布第一个野外UV数据集（我们称之为WildUV），该数据集包含来自1,892个身份的完整面部UV地图，用于研究目的。

##### URL
[http://arxiv.org/abs/1712.04695](http://arxiv.org/abs/1712.04695)

##### PDF
[http://arxiv.org/pdf/1712.04695](http://arxiv.org/pdf/1712.04695)

