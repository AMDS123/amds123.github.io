---
layout: post
title: "Just-in-Time Reconstruction: Inpainting Sparse Maps using Single View Depth Predictors as Priors"
date: 2018-05-11 04:08:59
categories: arXiv_CV
tags: arXiv_CV Sparse CNN Inference Prediction SLAM
author: Chamara Saroj Weerasekera, Thanuja Dharmasiri, Ravi Garg, Tom Drummond, Ian Reid
mathjax: true
---

* content
{:toc}

##### Abstract
We present ``just-in-time reconstruction" as real-time image-guided inpainting of a map with arbitrary scale and sparsity to generate a fully dense depth map for the image. In particular, our goal is to inpaint a sparse map --- obtained from either a monocular visual SLAM system or a sparse sensor --- using a single-view depth prediction network as a virtual depth sensor. We adopt a fairly standard approach to data fusion, to produce a fused depth map by performing inference over a novel fully-connected Conditional Random Field (CRF) which is parameterized by the input depth maps and their pixel-wise confidence weights. Crucially, we obtain the confidence weights that parameterize the CRF model in a data-dependent manner via Convolutional Neural Networks (CNNs) which are trained to model the conditional depth error distributions given each source of input depth map and the associated RGB image. Our CRF model penalises absolute depth error in its nodes and pairwise scale-invariant depth error in its edges, and the confidence-based fusion minimizes the impact of outlier input depth values on the fused result. We demonstrate the flexibility of our method by real-time inpainting of ORB-SLAM, Kinect, and LIDAR depth maps acquired both indoors and outdoors at arbitrary scale and varied amount of irregular sparsity.

##### Abstract (translated by Google)
我们提出“即时重建”作为实时图像引导的任意比例和稀疏性的地图的修补，为图像生成完全密集的深度图，特别是我们的目标是修复稀疏地图 -  - 从单目视觉SLAM系统或稀疏传感器获得 - 使用单视点深度预测网络作为虚拟深度传感器。我们采用相当标准的数据融合方法，通过执行推理生成融合深度图在一个新的全连通条件随机场（CRF）中，通过输入深度图和它们的像素置信度权重进行参数化。关键的是，我们通过卷积神经网络获得了以CRF模型参数化的置信度权重（CNNs），它们被训练成模拟给定输入深度图和相关RGB图像的每个源的条件深度误差分布。我们的CRF模型惩罚其节点中的绝对深度误差和成对比例不变深度其边缘误差，并且基于置信度的融合最小化异常值输入深度值对融合结果的影响。我们通过在室内和室外以任意比例和不规则稀疏量实时修复ORB-SLAM，Kinect和LIDAR深度图，展示了我们方法的灵活性。

##### URL
[http://arxiv.org/abs/1805.04239](http://arxiv.org/abs/1805.04239)

##### PDF
[http://arxiv.org/pdf/1805.04239](http://arxiv.org/pdf/1805.04239)

