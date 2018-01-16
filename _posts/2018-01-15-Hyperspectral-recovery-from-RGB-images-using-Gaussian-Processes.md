---
layout: post
title: "Hyperspectral recovery from RGB images using Gaussian Processes"
date: 2018-01-15 03:26:09
categories: arXiv_CV
tags: arXiv_CV Inference
author: Naveed Akhtar, Ajmal Mian
mathjax: true
---

* content
{:toc}

##### Abstract
Hyperspectral cameras preserve the fine spectral details of scenes that are generally lost in the traditional RGB cameras due to the gross quantization of radiance. These details are desirable in numerous imaging applications, nevertheless the high cost of hyperspectral hardware and the associated physical constraints currently limit the pervasive use of hyperspectral imaging. We take a computational approach to construct hyperspectral images using the RGB cameras of known spectral response, and assuming a prior over the imaged scene. Our approach first clusters training hyperspectral image patches and infers a set of Gaussian Processes~(GPs) to represent the naturally smooth reflectance spectra of materials in each cluster. The GPs and the clusters are then transformed to match the spectral quantization of the RGB camera. A patch from the test RGB image is assigned a matching cluster and it is represented by the transformed GPs for that cluster. The computed representation codes are combined with the original GPs to construct the desired hyperspectral signatures. The approach infers the Gaussian Processes using a model inspired by the Beta-Bernoulli Process and it encourages those to be non-negative to better approximate the positive reflectance values. We present the analytical expressions for the Bayesian inference over the proposed model. Thorough evaluation using three hyperspectral datasets demonstrates the effectiveness of the proposed technique.

##### Abstract (translated by Google)
高光谱相机保留了传统RGB相机中通常由于辐射的大量量化而丢失的场景的精细光谱细节。这些细节在许多成像应用中是需要的，但是高光谱硬件的高成本和相关的物理约束现在限制了高光谱成像的普遍使用。我们采用一种计算方法来使用已知光谱响应的RGB相机来构建高光谱图像，并且假设在成像的场景之前有先验的。我们的方法首先将训练的高光谱图像块聚类，并推断出一组高斯过程（GPs）来表示每个聚类中材料的自然光滑反射光谱。 GP和聚类然后被转换以匹配RGB相机的光谱量化。来自测试RGB图像的补丁被分配一个匹配的群集，并且由该群集的经转换的GP来表示。计算出的表示码与原始的GP结合起来构成所需的高光谱特征。该方法使用受贝尔努利过程启发的模型来推断高斯过程，并且鼓励那些非负的更好地近似正反射值。我们提出了在所提出的模型上的贝叶斯推断的解析表达式。使用三个高光谱数据集进行彻底的评估证明了所提出的技术的有效性。

##### URL
[https://arxiv.org/abs/1801.04654](https://arxiv.org/abs/1801.04654)

##### PDF
[https://arxiv.org/pdf/1801.04654](https://arxiv.org/pdf/1801.04654)

