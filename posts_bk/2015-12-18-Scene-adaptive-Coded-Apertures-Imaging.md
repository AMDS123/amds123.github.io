---
layout: post
title: "Scene-adaptive Coded Apertures Imaging"
date: 2015-12-18 02:13:08
categories: arXiv_CV
tags: arXiv_CV Relation
author: Xuehui Wang, Jinli Suo, Jingyi Yu, Yongdong Zhang, Qionghai Dai
mathjax: true
---

* content
{:toc}

##### Abstract
Coded aperture imaging systems have recently shown great success in recovering scene depth and extending the depth-of-field. The ideal pattern, however, would have to serve two conflicting purposes: 1) be broadband to ensure robust deconvolution and 2) has sufficient zero-crossings for a high depth discrepancy. This paper presents a simple but effective scene-adaptive coded aperture solution to bridge this gap. We observe that the geometric structures in a natural scene often exhibit only a few edge directions, and the successive frames are closely correlated. Therefore we adopt a spatial partitioning and temporal propagation scheme. In each frame, we address one principal direction by applying depth-discriminative codes along it and broadband codes along its orthogonal direction. Since within a frame only the regions with edge direction corresponding to its aperture code behaves well, we utilize the close among-frame correlation to propagate the high quality single frame results temporally to obtain high performance over the whole image lattice. To physically implement this scheme, we use a Liquid Crystal on Silicon (LCoS) microdisplay that permits fast changing pattern codes. Firstly, we capture the scene with a pinhole and analyze the scene content to determine primary edge orientations. Secondly, we sequentially apply the proposed coding scheme with these orientations in the following frames. Experiments on both synthetic and real scenes show that our technique is able to combine advantages of the state-of-the-art patterns for recovering better quality depth map and all-focus images.

##### Abstract (translated by Google)
编码孔径成像系统最近在恢复景深和扩大景深方面取得了巨大的成功。然而，理想的模式将不得不服务于两个冲突的目的：1）是宽带以确保强大的反卷积，以及2）对于高深度差异具有足够的过零点。本文提出了一个简单而有效的场景自适应编码孔径解决方案来填补这个空白。我们观察到自然场景中的几何结构通常只有少量的边缘方向，并且连续的帧紧密相关。因此我们采用空间划分和时间传播的方案。在每一帧中，我们通过沿着正交方向应用深度鉴别码和沿其正交方向的宽带码来解决一个主要方向。由于在一帧内只有边缘方向对应于其孔径编码的区域表现良好，我们利用紧密的帧间相关性在时间上传播高质量的单帧结果，以获得整个图像点阵的高性能。为了在物理上实现这个方案，我们使用硅基液晶（LCoS）微型显示器，允许快速改变模式代码。首先，我们用针孔捕捉场景，并分析场景内容，以确定主要的边缘方向。其次，我们在下面的帧中顺序地将所提出的编码方案与这些方向一起应用。在合成和真实场景的实验表明，我们的技术能够结合最先进的模式的优势，以恢复更好质量的深度图和全焦点图像。

##### URL
[https://arxiv.org/abs/1506.05942](https://arxiv.org/abs/1506.05942)

##### PDF
[https://arxiv.org/e-print/1506.05942](https://arxiv.org/e-print/1506.05942)

