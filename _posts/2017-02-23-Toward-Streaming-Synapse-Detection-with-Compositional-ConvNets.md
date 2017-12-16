---
layout: post
title: "Toward Streaming Synapse Detection with Compositional ConvNets"
date: 2017-02-23 20:48:13
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN Detection
author: Shibani Santurkar, David Budden, Alexander Matveev, Heather Berlin, Hayk Saribekyan, Yaron Meirovitch, Nir Shavit
mathjax: true
---

* content
{:toc}

##### Abstract
Connectomics is an emerging field in neuroscience that aims to reconstruct the 3-dimensional morphology of neurons from electron microscopy (EM) images. Recent studies have successfully demonstrated the use of convolutional neural networks (ConvNets) for segmenting cell membranes to individuate neurons. However, there has been comparatively little success in high-throughput identification of the intercellular synaptic connections required for deriving connectivity graphs. In this study, we take a compositional approach to segmenting synapses, modeling them explicitly as an intercellular cleft co-located with an asymmetric vesicle density along a cell membrane. Instead of requiring a deep network to learn all natural combinations of this compositionality, we train lighter networks to model the simpler marginal distributions of membranes, clefts and vesicles from just 100 electron microscopy samples. These feature maps are then combined with simple rules-based heuristics derived from prior biological knowledge. Our approach to synapse detection is both more accurate than previous state-of-the-art (7% higher recall and 5% higher F1-score) and yields a 20-fold speed-up compared to the previous fastest implementations. We demonstrate by reconstructing the first complete, directed connectome from the largest available anisotropic microscopy dataset (245 GB) of mouse somatosensory cortex (S1) in just 9.7 hours on a single shared-memory CPU system. We believe that this work marks an important step toward the goal of a microscope-pace streaming connectomics pipeline.

##### Abstract (translated by Google)
Connectomics是神经科学领域的一个新兴领域，旨在从电子显微镜（EM）图像重建神经元的三维形态。最近的研究成功地证明了使用卷积神经网络（ConvNets）来分割细胞膜以使神经元个体化。然而，在高通量鉴定导出连接图所需的细胞间突触连接方面，取得相对较少的成功。在这项研究中，我们采取成分方法来分割突触，明确地将它们建模为细胞间裂隙，其沿着细胞膜与不对称囊泡密度共同定位。我们不需要深入的网络来学习这种组合性的所有自然组合，而是训练更轻的网络，从100个电子显微镜样品中模拟膜，裂缝和囊泡的更简单的边缘分布。然后将这些特征图与基于先前生物学知识的基于规则的简单试探法相结合。我们的突触检测方法比以前最先进的方法更准确（召回率高7％，F1分数高5％），与之前的最快实现相比，其速度提高了20倍。我们通过在单个共享存储器CPU系统上仅用9.7小时从最大可用的各向异性显微镜数据集（245 GB）的鼠标体感皮层（S1）重建第一个完整的定向连接器来演示。我们相信，这项工作标志着向显微镜节奏流连接组合管道迈进的重要一步。

##### URL
[https://arxiv.org/abs/1702.07386](https://arxiv.org/abs/1702.07386)

##### PDF
[https://arxiv.org/pdf/1702.07386](https://arxiv.org/pdf/1702.07386)

