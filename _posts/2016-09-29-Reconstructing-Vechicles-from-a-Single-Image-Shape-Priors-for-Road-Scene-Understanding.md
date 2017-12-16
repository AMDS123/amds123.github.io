---
layout: post
title: "Reconstructing Vechicles from a Single Image: Shape Priors for Road Scene Understanding"
date: 2016-09-29 19:17:38
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN Optimization Inference
author: J. Krishna Murthy, G.V. Sai Krishna, Falak Chhaya, K. Madhava Krishna
mathjax: true
---

* content
{:toc}

##### Abstract
We present an approach for reconstructing vehicles from a single (RGB) image, in the context of autonomous driving. Though the problem appears to be ill-posed, we demonstrate that prior knowledge about how 3D shapes of vehicles project to an image can be used to reason about the reverse process, i.e., how shapes (back-)project from 2D to 3D. We encode this knowledge in \emph{shape priors}, which are learnt over a small keypoint-annotated dataset. We then formulate a shape-aware adjustment problem that uses the learnt shape priors to recover the 3D pose and shape of a query object from an image. For shape representation and inference, we leverage recent successes of Convolutional Neural Networks (CNNs) for the task of object and keypoint localization, and train a novel cascaded fully-convolutional architecture to localize vehicle \emph{keypoints} in images. The shape-aware adjustment then robustly recovers shape (3D locations of the detected keypoints) while simultaneously filling in occluded keypoints. To tackle estimation errors incurred due to erroneously detected keypoints, we use an Iteratively Re-weighted Least Squares (IRLS) scheme for robust optimization, and as a by-product characterize noise models for each predicted keypoint. We evaluate our approach on autonomous driving benchmarks, and present superior results to existing monocular, as well as stereo approaches.

##### Abstract (translated by Google)
我们提出了一种在自主驾驶情况下从单个（RGB）图像重建车辆的方法。虽然这个问题似乎是不适当的，但是我们证明了关于如何将三维形状的车辆投影到图像上的先前知识可以被用来推理关于相反的过程，即形状（背部）如何从2D投影到3D。我们在\ emph {shape priors}中编码这些知识，这些知识是通过一个小的关键点注释数据集学习的。然后，我们制定一个形状感知的调整问题，使用学习形状先验从图像恢复查询对象的三维姿势和形状。对于形状表示和推理，我们利用最近成功的卷积神经网络（CNNs）来完成对象和关键点定位任务，并且训练一种新的级联全卷积结构来对图像中的车辆关键点进行定位。形状感知调整然后强健地恢复形状（检测到的关键点的3D位置），同时填充被遮挡的关键点。为了处理由于错误检测关键点而导致的估计误差，我们使用迭代重新加权最小二乘（IRLS）方案进行鲁棒优化，并且作为副产品表征每个预测关键点的噪声模型。我们评估我们的自主驾驶基准测试方法，并为现有单眼以及立体声方法提供出色的结果。

##### URL
[https://arxiv.org/abs/1609.09468](https://arxiv.org/abs/1609.09468)

##### PDF
[https://arxiv.org/pdf/1609.09468](https://arxiv.org/pdf/1609.09468)

