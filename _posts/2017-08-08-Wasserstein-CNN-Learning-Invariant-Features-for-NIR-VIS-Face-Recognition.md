---
layout: post
title: "Wasserstein CNN: Learning Invariant Features for NIR-VIS Face Recognition"
date: 2017-08-08 09:07:34
categories: arXiv_CV
tags: arXiv_CV Face CNN Relation Recognition Face_Recognition
author: Ran He, Xiang Wu, Zhenan Sun, Tieniu Tan
mathjax: true
---

* content
{:toc}

##### Abstract
Heterogeneous face recognition (HFR) aims to match facial images acquired from different sensing modalities with mission-critical applications in forensics, security and commercial sectors. However, HFR is a much more challenging problem than traditional face recognition because of large intra-class variations of heterogeneous face images and limited training samples of cross-modality face image pairs. This paper proposes a novel approach namely Wasserstein CNN (convolutional neural networks, or WCNN for short) to learn invariant features between near-infrared and visual face images (i.e. NIR-VIS face recognition). The low-level layers of WCNN are trained with widely available face images in visual spectrum. The high-level layer is divided into three parts, i.e., NIR layer, VIS layer and NIR-VIS shared layer. The first two layers aims to learn modality-specific features and NIR-VIS shared layer is designed to learn modality-invariant feature subspace. Wasserstein distance is introduced into NIR-VIS shared layer to measure the dissimilarity between heterogeneous feature distributions. So W-CNN learning aims to achieve the minimization of Wasserstein distance between NIR distribution and VIS distribution for invariant deep feature representation of heterogeneous face images. To avoid the over-fitting problem on small-scale heterogeneous face data, a correlation prior is introduced on the fully-connected layers of WCNN network to reduce parameter space. This prior is implemented by a low-rank constraint in an end-to-end network. The joint formulation leads to an alternating minimization for deep feature representation at training stage and an efficient computation for heterogeneous data at testing stage. Extensive experiments on three challenging NIR-VIS face recognition databases demonstrate the significant superiority of Wasserstein CNN over state-of-the-art methods.

##### Abstract (translated by Google)
异构人脸识别（HFR）旨在将从不同传感模式获得的面部图像与法医学，安全和商业领域的关键任务应用进行匹配。然而，由于异类人脸图像的大类内部变化和跨模态人脸图像对的有限训练样本，HFR是比传统人脸识别更具挑战性的问题。本文提出了一种新颖的方法，即Wasserstein CNN（卷积神经网络，简称WCNN），用于学习近红外与人脸图像（即NIR-VIS人脸识别）之间的不变特征。在视觉光谱中，WCNN的低层图像用广泛可用的人脸图像进行训练。高层分为三个部分，即NIR层，VIS层和NIR-VIS共享层。前两层旨在学习模态特有的特征，NIR-VIS共享层用于学习形态不变特征子空间。在NIR-VIS共享层中引入Wasserstein距离来度量异构特征分布的不相似度。因此，W-CNN学习的目的在于实现NIR分布与VIS分布之间的Wasserstein距离最小化，以实现异构人脸图像不变的深度特征表示。为了避免小规模异构人脸数据的过度拟合问题，在WCNN网络的全连接层上引入相关优先，以减少参数空间。这个先验是通过端到端网络中的低级约束实现的。联合公式导致训练阶段深度特征表示的交替最小化，以及测试阶段对异构数据的有效计算。在三个具有挑战性的NIR-VIS人脸识别数据库上的大量实验证明了Wasserstein CNN相对于最新方法的显着优势。

##### URL
[https://arxiv.org/abs/1708.02412](https://arxiv.org/abs/1708.02412)

##### PDF
[https://arxiv.org/pdf/1708.02412](https://arxiv.org/pdf/1708.02412)

