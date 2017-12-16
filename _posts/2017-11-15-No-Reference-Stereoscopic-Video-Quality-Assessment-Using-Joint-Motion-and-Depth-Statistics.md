---
layout: post
title: "No Reference Stereoscopic Video Quality Assessment Using Joint Motion and Depth Statistics"
date: 2017-11-15 09:52:23
categories: arXiv_CV
tags: arXiv_CV QA Prediction
author: Appina Balasubramanyam, Jalli Akshith, Battula Shanmukh Srinivas, Channappayya S Sumohana
mathjax: true
---

* content
{:toc}

##### Abstract
We present a no reference (NR) quality assessment algorithm for assessing the perceptual quality of natural stereoscopic 3D (S3D) videos. This work is inspired by our finding that the joint statistics of the subband coefficients of motion (optical flow or motion vector magnitude) and depth (disparity map) of natural S3D videos possess a unique signature. Specifically, we empirically show that the joint statistics of the motion and depth subband coefficients of S3D video frames can be modeled accurately using a Bivariate Generalized Gaussian Distribution (BGGD). We then demonstrate that the parameters of the BGGD model possess the ability to discern quality variations in S3D videos. Therefore, the BGGD model parameters are employed as motion and depth quality features. In addition to these features, we rely on a frame level spatial quality feature that is computed using a robust off the shelf NR image quality assessment (IQA) algorithm. These frame level motion, depth and spatial features are consolidated and used with the corresponding S3D video's difference mean opinion score (DMOS) labels for supervised learning using support vector regression (SVR). The overall quality of an S3D video is computed by averaging the frame level quality predictions of the constituent video frames. The proposed algorithm, dubbed Video QUality Evaluation using MOtion and DEpth Statistics (VQUEMODES) is shown to outperform the state of the art methods when evaluated over the IRCCYN and LFOVIA S3D subjective quality assessment databases.

##### Abstract (translated by Google)
我们提出了一个无参考（NR）质量评估算法来评估自然立体3D（S3D）视频的感知质量。这项工作受到我们的发现的启发，即自然S3D视频的子带运动系数（光流或运动矢量幅度）和深度（视差图）的联合统计具有独特的签名。具体来说，我们凭经验证明，可以使用双变量广义高斯分布（BGGD）来精确地建模S3D视频帧的运动和深度子带系数的联合统计。然后我们证明BGGD模型的参数能够辨别S3D视频中的质量变化。因此，BGGD模型参数被用作运动和深度质量特征。除了这些特征之外，我们依赖于使用强健的现成NR图像质量评估（IQA）算法计算的帧级空间质量特征。这些帧级运动，深度和空间特征被合并，并且与使用支持向量回归（SVR）的相应S3D视频的差异平均意见分数（DMOS）标签一起用于监督学习。通过对组成视频帧的帧级质量预测进行平均来计算S3D视频的整体质量。在IRCCYN和LFOVIA S3D主观质量评估数据库上评估时，所提出的使用MOtion和DEpth统计的视频质量评估（VQUEMODES）的算法被证明优于现有技术方法。

##### URL
[https://arxiv.org/abs/1711.05480](https://arxiv.org/abs/1711.05480)

##### PDF
[https://arxiv.org/pdf/1711.05480](https://arxiv.org/pdf/1711.05480)

