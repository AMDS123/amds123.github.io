---
layout: post
title: "Digging Into Self-Supervised Monocular Depth Estimation"
date: 2018-06-04 17:58:05
categories: arXiv_CV
tags: arXiv_CV
author: Cl&#xe9;ment Godard, Oisin Mac Aodha, Gabriel Brostow
mathjax: true
---

* content
{:toc}

##### Abstract
Depth-sensing is important for both navigation and scene understanding. However, procuring RGB images with corresponding depth data for training deep models is challenging; large-scale, varied, datasets with ground truth training data are scarce. Consequently, several recent methods have proposed treating the training of monocular color-to-depth estimation networks as an image reconstruction problem, thus forgoing the need for ground truth depth. 
 There are multiple concepts and design decisions for these networks that seem sensible, but give mixed or surprising results when tested. For example, binocular stereo as the source of self-supervision seems cumbersome and hard to scale, yet results are less blurry compared to training with monocular videos. Such decisions also interplay with questions about architectures, loss functions, image scales, and motion handling. In this paper, we propose a simple yet effective model, with several general architectural and loss innovations, that surpasses all other self-supervised depth estimation approaches on KITTI.

##### Abstract (translated by Google)
深度感应对于导航和场景理解都很重要。然而，为深度训练模型采购具有相应深度数据的RGB图像具有挑战性;具有地面实况训练数据的大规模，多样化的数据集很少。因此，最近的几种方法已经提出将单眼颜色 - 深度估计网络的训练视为图像重建问题，因此不需要地面真实深度。
 这些网络有多种概念和设计决策，看起来很合理，但在测试时给出混合或令人惊讶的结果。例如，作为自我监控来源的双目立体视觉看起来很笨重，难以扩展，但与使用单眼视频进行训练相比，结果并不那么模糊。这些决策还与有关架构，损失函数，图像尺度和运动处理的问题相互作用。在本文中，我们提出了一个简单而有效的模型，其中包含几个通用的架构和损失创新，超越了KITTI的所有其他自我监督深度估计方法。

##### URL
[http://arxiv.org/abs/1806.01260](http://arxiv.org/abs/1806.01260)

##### PDF
[http://arxiv.org/pdf/1806.01260](http://arxiv.org/pdf/1806.01260)

