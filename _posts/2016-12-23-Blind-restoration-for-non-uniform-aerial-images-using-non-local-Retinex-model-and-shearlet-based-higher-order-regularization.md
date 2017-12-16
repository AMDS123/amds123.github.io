---
layout: post
title: "Blind restoration for non-uniform aerial images using non-local Retinex model and shearlet-based higher-order regularization"
date: 2016-12-23 17:02:16
categories: arXiv_CV
tags: arXiv_CV Regularization GAN
author: Rui Chen, Huizhu Jia, Xiaodong Xie, Wen Gao
mathjax: true
---

* content
{:toc}

##### Abstract
Aerial images are often degraded by space-varying motion blur and simultaneous uneven illumination. To recover high-quality aerial image from its non-uniform version, we propose a novel patch-wise restoration approach based on a key observation that the degree of blurring is inevitably affected by the illuminated conditions. A non-local Retinex model is developed to accurately estimate the reflectance component from the degraded aerial image. Thereafter the uneven illumination is corrected well. And then non-uniform coupled blurring in the enhanced reflectance image is alleviated and transformed towards uniform distribution, which will facilitate the subsequent deblurring. For constructing the multi-scale sparsified regularizer, the discrete shearlet transform is improved to better represent anisotropic image features in term of directional sensitivity and selectivity. In addition, a new adaptive variant of total generalized variation is proposed for the structure-preserving regularizer. These complementary regularizers are elegantly integrated into an objective function. The final deblurred image with uniform illumination can be extracted by applying the fast alternating direction scheme to solve the derived function. The experimental results demonstrate that our algorithm can not only remove both the space-varying illumination and motion blur in the aerial image effectively but also recover the abundant details of aerial scenes with top-level objective and subjective quality, and outperforms other state-of-the-art restoration methods.

##### Abstract (translated by Google)
空中图像通常由于空间变化的运动模糊和同时不均匀的照明而降低。为了从其非均匀版本恢复高质量的航拍图像，我们提出了一种基于关键观察的新颖的补片复原方法，即模糊程度不可避免地受照明条件的影响。开发了非局部Retinex模型来准确估计来自退化的空间图像的反射分量。此后，不均匀照明被很好地校正。然后增强反射图像中的非均匀耦合模糊被缓解并转化为均匀分布，这将有助于随后的去模糊。为了构造多尺度稀疏正则化器，对方向敏感性和选择性方面的离散剪切变换进行了改进，以更好地表示各向异性的图像特征。此外，还提出了一种适用于结构保持调节器的全广义变分自适应变量。这些互补的正规化者被优雅地整合到一个目标函数中。通过应用快速交替方向方案来解决导出的函数，可以提取具有均匀照明的最终去模糊图像。实验结果表明，该算法不仅可以有效去除航拍图像中的空间变化照明和运动模糊，还可以恢复具有最高客观质量和主观质量的航拍场景的丰富细节，最先进的修复方法。

##### URL
[https://arxiv.org/abs/1612.08037](https://arxiv.org/abs/1612.08037)

##### PDF
[https://arxiv.org/pdf/1612.08037](https://arxiv.org/pdf/1612.08037)

