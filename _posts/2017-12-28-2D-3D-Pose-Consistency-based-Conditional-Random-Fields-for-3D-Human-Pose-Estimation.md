---
layout: post
title: "2D-3D Pose Consistency-based Conditional Random Fields for 3D Human Pose Estimation"
date: 2017-12-28 05:31:47
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Inference
author: Ju Yong Chang, Kyoung Mu Lee
mathjax: true
---

* content
{:toc}

##### Abstract
This study considers the 3D human pose estimation problem in a single RGB image by proposing a conditional random field (CRF) model over 2D poses, in which the 3D pose is obtained as a byproduct of the inference process. The unary term of the proposed CRF model is defined based on a powerful heat-map regression network, which has been proposed for 2D human pose estimation. This study also presents a regression network for lifting the 2D pose to 3D pose and proposes the prior term based on the consistency between the estimated 3D pose and the 2D pose. To obtain the approximate solution of the proposed CRF model, the N-best strategy is adopted. The proposed inference algorithm can be viewed as sequential processes of bottom-up generation of 2D and 3D pose proposals from the input 2D image based on deep networks and top-down verification of such proposals by checking their consistencies. To evaluate the proposed method, we use two large-scale datasets: Human3.6M and HumanEva. Experimental results show that the proposed method achieves the state-of-the-art 3D human pose estimation performance.

##### Abstract (translated by Google)
本研究通过在二维姿态上提出条件随机场（CRF）模型来考虑单个RGB图像中的三维人体姿态估计问题，其中三维姿态作为推理过程的副产品而获得。所提出的CRF模型的一元术语是基于强大的热图回归网络来定义的，该网络已经被提出用于2D人体姿态估计。这项研究还提出了一个回归网络，提升二维姿态到三维姿态，并根据估计的三维姿态和二维姿态之间的一致性提出了前一项。为了获得所提出的CRF模型的近似解，采用N-最佳策略。所提出的推理算法可以视为基于深度网络从输入的二维图像自下而上生成二维和三维姿态的顺序过程，并通过检查这些提议的一致性来自上而下地验证。为了评估所提出的方法，我们使用两个大规模的数据集：Human3.6M和HumanEva。实验结果表明，该方法实现了最先进的三维人体姿态估计性能。

##### URL
[http://arxiv.org/abs/1704.03986](http://arxiv.org/abs/1704.03986)

##### PDF
[http://arxiv.org/pdf/1704.03986](http://arxiv.org/pdf/1704.03986)

