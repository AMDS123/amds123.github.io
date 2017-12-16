---
layout: post
title: "Deep Multitask Architecture for Integrated 2D and 3D Human Sensing"
date: 2017-01-31 10:52:48
categories: arXiv_CV
tags: arXiv_CV Segmentation Recognition
author: Alin-Ionut Popa, Mihai Zanfir, Cristian Sminchisescu
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a deep multitask architecture for \emph{fully automatic 2d and 3d human sensing} (DMHS), including \emph{recognition and reconstruction}, in \emph{monocular images}. The system computes the figure-ground segmentation, semantically identifies the human body parts at pixel level, and estimates the 2d and 3d pose of the person. The model supports the joint training of all components by means of multi-task losses where early processing stages recursively feed into advanced ones for increasingly complex calculations, accuracy and robustness. The design allows us to tie a complete training protocol, by taking advantage of multiple datasets that would otherwise restrictively cover only some of the model components: complex 2d image data with no body part labeling and without associated 3d ground truth, or complex 3d data with limited 2d background variability. In detailed experiments based on several challenging 2d and 3d datasets (LSP, HumanEva, Human3.6M), we evaluate the sub-structures of the model, the effect of various types of training data in the multitask loss, and demonstrate that state-of-the-art results can be achieved at all processing levels. We also show that in the wild our monocular RGB architecture is perceptually competitive to a state-of-the art (commercial) Kinect system based on RGB-D data.

##### Abstract (translated by Google)
我们提出了\ emph {全自动二维和三维人类感知}（DMHS）的深度多任务架构，包括\ emph {单眼图像}中的\ emph {识别和重建}。该系统计算图形地面分割，在像素级别语义识别人体部位，并估计人的二维和三维姿态。该模型通过多任务损失来支持所有组件的联合训练，其中早期处理阶段递归地馈入先进处理阶段，用于越来越复杂的计算，准确性和鲁棒性。该设计允许我们通过利用多个数据集来绑定完整的训练协议，否则这些数据集将限制性地仅覆盖一些模型组件：复杂的2D图像数据，没有身体部位标记，没有相关的3D地面真实，或复杂的3D数据与有限的二维背景变化。在基于几个具有挑战性的2d和3d数据集（LSP，HumanEva，Human3.6M）的详细实验中，我们评估了模型的子结构，各种类型的训练数据在多任务丢失中的效果，可以在所有的处理级别上实现最先进的结果。我们还表明，在野外，我们的单眼RGB架构与基于RGB-D数据的最先进的（商业）Kinect系统相比，具有明显的竞争性。

##### URL
[https://arxiv.org/abs/1701.08985](https://arxiv.org/abs/1701.08985)

##### PDF
[https://arxiv.org/pdf/1701.08985](https://arxiv.org/pdf/1701.08985)

