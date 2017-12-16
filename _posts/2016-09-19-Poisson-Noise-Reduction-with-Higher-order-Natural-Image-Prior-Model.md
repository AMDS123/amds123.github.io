---
layout: post
title: "Poisson Noise Reduction with Higher-order Natural Image Prior Model"
date: 2016-09-19 13:35:14
categories: arXiv_CV
tags: arXiv_CV Inference
author: Wensen Feng, Hong Qiao, Yunjin Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Poisson denoising is an essential issue for various imaging applications, such as night vision, medical imaging and microscopy. State-of-the-art approaches are clearly dominated by patch-based non-local methods in recent years. In this paper, we aim to propose a local Poisson denoising model with both structure simplicity and good performance. To this end, we consider a variational modeling to integrate the so-called Fields of Experts (FoE) image prior, that has proven an effective higher-order Markov Random Fields (MRF) model for many classic image restoration problems. We exploit several feasible variational variants for this task. We start with a direct modeling in the original image domain by taking into account the Poisson noise statistics, which performs generally well for the cases of high SNR. However, this strategy encounters problem in cases of low SNR. Then we turn to an alternative modeling strategy by using the Anscombe transform and Gaussian statistics derived data term. We retrain the FoE prior model directly in the transform domain. With the newly trained FoE model, we end up with a local variational model providing strongly competitive results against state-of-the-art non-local approaches, meanwhile bearing the property of simple structure. Furthermore, our proposed model comes along with an additional advantage, that the inference is very efficient as it is well-suited for parallel computation on GPUs. For images of size $512 \times 512$, our GPU implementation takes less than 1 second to produce state-of-the-art Poisson denoising performance.

##### Abstract (translated by Google)
泊松去噪是各种成像应用（诸如夜视，医学成像和显微术）的基本问题。国家的最先进的方法显然是由补丁为基础的非本地方法近年来占主导地位。本文旨在提出一种结构简单，性能良好的局部泊松去噪模型。为此，我们考虑了一个变化的模型来整合所谓的专家领域（FoE）图像，这证明了许多经典图像恢复问题的有效的高阶马尔可夫随机场（MRF）模型。我们利用几个可行的变化变量来完成这个任务。我们首先考虑泊松噪声统计，在原始图像域中进行直接建模，对于高信噪比的情况通常表现良好。但是，这种策略在低信噪比情况下遇到问题。然后我们转向使用Anscombe变换和高斯统计数据项的替代建模策略。我们直接在变换域重新训练FoE先验模型。利用新近训练过的FoE模型，我们得到了一个局部变分模型，与最先进的非局部方法相比，提供了非常有竞争力的结果，同时又具有结构简单的性质。此外，我们提出的模型带来了额外的优势，推理非常有效，因为它非常适合在GPU上进行并行计算。对于尺寸为$ 512 \ times 512 $的图片，我们的GPU实现花费不到1秒的时间就可以产生最先进的泊松降噪性能。

##### URL
[https://arxiv.org/abs/1609.05722](https://arxiv.org/abs/1609.05722)

##### PDF
[https://arxiv.org/pdf/1609.05722](https://arxiv.org/pdf/1609.05722)

