---
layout: post
title: "Adversarial Deformation Regularization for Training Image Registration Neural Networks"
date: 2018-05-27 17:56:51
categories: arXiv_CV
tags: arXiv_CV Regularization Adversarial Segmentation CNN Inference
author: Yipeng Hu, Eli Gibson, Nooshin Ghavami, Ester Bonmati, Caroline M. Moore, Mark Emberton, Tom Vercauteren, J. Alison Noble, Dean C. Barratt
mathjax: true
---

* content
{:toc}

##### Abstract
We describe an adversarial learning approach to constrain convolutional neural network training for image registration, replacing heuristic smoothness measures of displacement fields often used in these tasks. Using minimally-invasive prostate cancer intervention as an example application, we demonstrate the feasibility of utilizing biomechanical simulations to regularize a weakly-supervised anatomical-label-driven registration network for aligning pre-procedural magnetic resonance (MR) and 3D intra-procedural transrectal ultrasound (TRUS) images. A discriminator network is optimized to distinguish the registration-predicted displacement fields from the motion data simulated by finite element analysis. During training, the registration network simultaneously aims to maximize similarity between anatomical labels that drives image alignment and to minimize an adversarial generator loss that measures divergence between the predicted- and simulated deformation. The end-to-end trained network enables efficient and fully-automated registration that only requires an MR and TRUS image pair as input, without anatomical labels or simulated data during inference. 108 pairs of labelled MR and TRUS images from 76 prostate cancer patients and 71,500 nonlinear finite-element simulations from 143 different patients were used for this study. We show that, with only gland segmentation as training labels, the proposed method can help predict physically plausible deformation without any other smoothness penalty. Based on cross-validation experiments using 834 pairs of independent validation landmarks, the proposed adversarial-regularized registration achieved a target registration error of 6.3 mm that is significantly lower than those from several other regularization methods.

##### Abstract (translated by Google)
我们描述了一种敌对学习方法来约束用于图像配准的卷积神经网络训练，取代了这些任务中经常使用的位移场的启发式光滑度量。以微创前列腺癌干预为例，我们证明了利用生物力学模拟来调整弱监督的解剖标记驱动的配准网络以对准手术前磁共振（MR）和3D手术中经直肠内超声的可行性（TRUS）图像。鉴别器网络经过优化，可将注册预测位移场与有限元分析模拟的运动数据进行区分。在训练过程中，配准网络同时旨在最大限度地提高解剖标记之间的相似性，从而驱动图像对齐，并最大限度地减少测量预测变形和模拟变形之间的分歧的对手发生器损失。端到端的训练网络可实现高效且全自动化的注册，仅需要MR和TRUS图像对作为输入，而无需解析标签或推理期间的模拟数据。本研究使用来自76名前列腺癌患者的108对标记的MR和TRUS图像和来自143名不同患者的71,500个非线性有限元模拟。我们表明，只有腺体分割作为训练标签，所提出的方法可以帮助预测物理上似真的变形，而没有任何其他的光滑度损失。基于使用834对独立验证界标的交叉验证实验，所提出的对抗 - 正则化配准实现了6.3mm的目标配准误差，其明显低于来自其他几种正则化方法的配准。

##### URL
[http://arxiv.org/abs/1805.10665](http://arxiv.org/abs/1805.10665)

##### PDF
[http://arxiv.org/pdf/1805.10665](http://arxiv.org/pdf/1805.10665)

