---
layout: post
title: "Intraoperative Organ Motion Models with an Ensemble of Conditional Generative Adversarial Networks"
date: 2017-09-05 21:14:39
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Yipeng Hu, Eli Gibson, Tom Vercauteren, Hashim U. Ahmed, Mark Emberton, Caroline M. Moore, J. Alison Noble, Dean C. Barratt
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we describe how a patient-specific, ultrasound-probe-induced prostate motion model can be directly generated from a single preoperative MR image. Our motion model allows for sampling from the conditional distribution of dense displacement fields, is encoded by a generative neural network conditioned on a medical image, and accepts random noise as additional input. The generative network is trained by a minimax optimisation with a second discriminative neural network, tasked to distinguish generated samples from training motion data. In this work, we propose that 1) jointly optimising a third conditioning neural network that pre-processes the input image, can effectively extract patient-specific features for conditioning; and 2) combining multiple generative models trained separately with heuristically pre-disjointed training data sets can adequately mitigate the problem of mode collapse. Trained with diagnostic T2-weighted MR images from 143 real patients and 73,216 3D dense displacement fields from finite element simulations of intraoperative prostate motion due to transrectal ultrasound probe pressure, the proposed models produced physically-plausible patient-specific motion of prostate glands. The ability to capture biomechanically simulated motion was evaluated using two errors representing generalisability and specificity of the model. The median values, calculated from a 10-fold cross-validation, were 2.8+/-0.3 mm and 1.7+/-0.1 mm, respectively. We conclude that the introduced approach demonstrates the feasibility of applying state-of-the-art machine learning algorithms to generate organ motion models from patient images, and shows significant promise for future research.

##### Abstract (translated by Google)
在本文中，我们描述了如何从一个单一的术前磁共振图像直接生成一个病人特定的超声探头诱导前列腺运动模型。我们的运动模型允许从密集位移场的条件分布进行采样，由生成的医学图像的神经网络编码，并接受随机噪声作为附加输入。生成网络通过使用第二判别式神经网络的极大极小优化训练，其任务是将生成的样本与训练运动数据区分开来。在这项工作中，我们提出1）联合优化一个预处理输入图像的第三个调节神经网络，可以有效地提取患者特定的调节特征; 2）将分别训练的多个生成模型与启发式预先脱节的训练数据集组合可以充分地减轻模式崩溃的问题。对来自143名真实患者的诊断性T2加权MR图像和73,216个三维密集位移场进行了训练，这些位置来自由经直肠超声探头压力引起的术中前列腺运动的有限元模拟，所提出的模型产生前列腺的物理上合理的患者特异性运动。捕获生物力学模拟运动的能力使用表示模型的一般性和特异性的两个误差进行评估。由10倍交叉验证计算的中值分别为2.8 +/- 0.3mm和1.7 +/- 0.1mm。我们得出的结论是，引入的方法表明应用最先进的机器学习算法从患者图像生成器官运动模型的可行性，并显示未来研究的重要前景。

##### URL
[https://arxiv.org/abs/1709.02255](https://arxiv.org/abs/1709.02255)

##### PDF
[https://arxiv.org/pdf/1709.02255](https://arxiv.org/pdf/1709.02255)

