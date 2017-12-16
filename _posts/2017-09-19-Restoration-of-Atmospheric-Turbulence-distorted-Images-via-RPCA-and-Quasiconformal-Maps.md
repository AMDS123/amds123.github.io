---
layout: post
title: "Restoration of Atmospheric Turbulence-distorted Images via RPCA and Quasiconformal Maps"
date: 2017-09-19 03:40:28
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Chun Pong Lau, Yu Hin Lai, Lok Ming Lui
mathjax: true
---

* content
{:toc}

##### Abstract
We address the problem of restoring a high-quality image from an observed image sequence strongly distorted by atmospheric turbulence. A novel algorithm is proposed in this paper to reduce geometric distortion as well as space-and-time-varying blur due to strong turbulence. By considering a suitable energy functional, our algorithm first obtains a sharp reference image and a subsampled image sequence containing sharp and mildly distorted image frames with respect to the reference image. The subsampled image sequence is then stabilized by applying the Robust Principal Component Analysis (RPCA) on the deformation fields between image frames and warping the image frames by a quasiconformal map associated with the low-rank part of the deformation matrix. After image frames are registered to the reference image, the low-rank part of them are deblurred via a blind deconvolution, and the deblurred frames are then fused with the enhanced sparse part. Experiments have been carried out on both synthetic and real turbulence-distorted video. Results demonstrate that our method is effective in alleviating distortions and blur, restoring image details and enhancing visual quality.

##### Abstract (translated by Google)
我们解决了从大气湍流强烈扭曲的观察图像序列恢复高质量图像的问题。本文提出了一种新的算法，以减少由强湍流引起的几何失真以及时空变化的模糊。通过考虑适当的能量函数，我们的算法首先获得包含相对于参考图像的锐利和轻微失真的图像帧的锐利的参考图像和二次采样的图像序列。然后通过对图像帧之间的变形场应用鲁棒主分量分析（RPCA）并通过与变形矩阵的低秩部分相关联的准共形映射使图像帧翘曲来使二次采样的图像序列稳定。将图像帧注册到参考图像后，通过盲解卷积对其低一部分进行去模糊处理，然后将去模糊的帧与增强后的稀疏部分进行融合。对合成和真实湍流扭曲的视频进行了实验。结果表明，我们的方法是有效的减轻扭曲和模糊，恢复图像的细节和提高视觉质量。

##### URL
[https://arxiv.org/abs/1704.03140](https://arxiv.org/abs/1704.03140)

##### PDF
[https://arxiv.org/pdf/1704.03140](https://arxiv.org/pdf/1704.03140)

