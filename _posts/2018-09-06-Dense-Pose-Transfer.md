---
layout: post
title: "Dense Pose Transfer"
date: 2018-09-06 13:53:00
categories: arXiv_CV
tags: arXiv_CV Adversarial Face Pose_Estimation CNN Prediction
author: Natalia Neverova, Riza Alp Guler, Iasonas Kokkinos
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we integrate ideas from surface-based modeling with neural synthesis: we propose a combination of surface-based pose estimation and deep generative models that allows us to perform accurate pose transfer, i.e. synthesize a new image of a person based on a single image of that person and the image of a pose donor. We use a dense pose estimation system that maps pixels from both images to a common surface-based coordinate system, allowing the two images to be brought in correspondence with each other. We inpaint and refine the source image intensities in the surface coordinate system, prior to warping them onto the target pose. These predictions are fused with those of a convolutional predictive module through a neural synthesis module allowing for training the whole pipeline jointly end-to-end, optimizing a combination of adversarial and perceptual losses. We show that dense pose estimation is a substantially more powerful conditioning input than landmark-, or mask-based alternatives, and report systematic improvements over state of the art generators on DeepFashion and MVC datasets.

##### Abstract (translated by Google)
在这项工作中，我们将基于表面的建模和神经合成的想法融合在一起：我们提出了基于表面的姿势估计和深度生成模型的组合，使我们能够执行准确的姿势转移，即基于单个合成人的新图像那个人的形象和姿势捐赠者的形象。我们使用密集的姿态估计系统，将来自两个图像的像素映射到基于表面的公共坐标系，允许两个图像彼此对应。在将它们翘曲到目标姿势之前，我们在表面坐标系中绘制和细化源图像强度。这些预测通过神经综合模块与卷积预测模块的预测融合，允许端到端地联合训练整个管道，优化对抗和感知损失的组合。我们表明，密集姿态估计是比基于地标或基于掩模的替代方案更强大的调节输入，并且报告了对DeepFashion和MVC数据集上的现有技术生成器的系统改进。

##### URL
[http://arxiv.org/abs/1809.01995](http://arxiv.org/abs/1809.01995)

##### PDF
[http://arxiv.org/pdf/1809.01995](http://arxiv.org/pdf/1809.01995)

