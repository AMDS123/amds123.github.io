---
layout: post
title: "Direct White Matter Bundle Segmentation using Stacked U-Nets"
date: 2017-03-06 14:21:49
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Jakob Wasserthal, Peter F. Neher, Fabian Isensee, Klaus H. Maier-Hein
mathjax: true
---

* content
{:toc}

##### Abstract
The state-of-the-art method for automatically segmenting white matter bundles in diffusion-weighted MRI is tractography in conjunction with streamline cluster selection. This process involves long chains of processing steps which are not only computationally expensive but also complex to setup and tedious with respect to quality control. Direct bundle segmentation methods treat the task as a traditional image segmentation problem. While they so far did not deliver competitive results, they can potentially mitigate many of the mentioned issues. We present a novel supervised approach for direct tract segmentation that shows major performance gains. It builds upon a stacked U-Net architecture which is trained on manual bundle segmentations from Human Connectome Project subjects. We evaluate our approach \textit{in vivo} as well as \textit{in silico} using the ISMRM 2015 Tractography Challenge phantom dataset. We achieve human segmentation performance and a major performance gain over previous pipelines. We show how the learned spatial priors efficiently guide the segmentation even at lower image qualities with little quality loss.

##### Abstract (translated by Google)
在扩散加权MRI中自动分割白质束的最先进的方法是结合流线簇选择的束缚。这个过程涉及长链处理步骤，这不仅在计算上昂贵，而且在质量控制方面也很复杂。直接束分割方法将该任务视为传统的图像分割问题。虽然迄今为止他们没有提供有竞争力的结果，但他们可以潜在地减轻许多提到的问题。我们提出了一个新的监督方法直接分割渠道，显示主要的性能收益。它建立在一个堆叠的U-Net架构上，该架构经过人类Connectome项目主题的手动捆绑分割培训。我们使用ISMRM 2015 Tractography Challenge幻影数据集评估我们的方法\ textit {in vivo}以及\ textit {in silico}。我们实现了人力细分表现，并取得了比之前的管道更大的性能提升。我们展示了学习的空间先验如何有效地引导分割，即使在较低的图像质量下，质量损失也很小。

##### URL
[https://arxiv.org/abs/1703.02036](https://arxiv.org/abs/1703.02036)

##### PDF
[https://arxiv.org/pdf/1703.02036](https://arxiv.org/pdf/1703.02036)

