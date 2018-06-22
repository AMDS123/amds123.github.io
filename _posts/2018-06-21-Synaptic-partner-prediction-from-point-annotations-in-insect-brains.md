---
layout: post
title: "Synaptic partner prediction from point annotations in insect brains"
date: 2018-06-21 12:42:46
categories: arXiv_CV
tags: arXiv_CV Segmentation Classification Prediction
author: Julia Buhmann, Renate Krause, Rodrigo Ceballos Lentini, Nils Eckstein, Matthew Cook, Srinivas Turaga, Jan Funke
mathjax: true
---

* content
{:toc}

##### Abstract
High-throughput electron microscopy allows recording of lar- ge stacks of neural tissue with sufficient resolution to extract the wiring diagram of the underlying neural network. Current efforts to automate this process focus mainly on the segmentation of neurons. However, in order to recover a wiring diagram, synaptic partners need to be identi- fied as well. This is especially challenging in insect brains like Drosophila melanogaster, where one presynaptic site is associated with multiple post- synaptic elements. Here we propose a 3D U-Net architecture to directly identify pairs of voxels that are pre- and postsynaptic to each other. To that end, we formulate the problem of synaptic partner identification as a classification problem on long-range edges between voxels to encode both the presence of a synaptic pair and its direction. This formulation allows us to directly learn from synaptic point annotations instead of more ex- pensive voxel-based synaptic cleft or vesicle annotations. We evaluate our method on the MICCAI 2016 CREMI challenge and improve over the current state of the art, producing 3% fewer errors than the next best method.

##### Abstract (translated by Google)
高通量电子显微镜允许以足够的分辨率记录大量神经组织的堆栈，以提取基础神经网络的接线图。目前，使这一过程自动化的努力主要集中在神经元的分割上。但是，为了恢复接线图，还需要识别突触伙伴。这对于果蝇等果蝇特别具有挑战性，果蝇中的一个突触前位点与多个突触后元件相关。在这里，我们提出了一种3D U-Net架构来直接识别彼此之前和之后突触的体素对。为此，我们将突触伴侣识别的问题制定为体素之间长程边缘上的分类问题，以编码突触对的存在及其方向。这个公式允许我们直接从突触点注释中学习，而不是更加昂贵的基于体素的突触间隙或囊泡注释。我们在MICCAI 2016 CREMI挑战中评估我们的方法，并改进当前技术水平，比下一个最佳方法产生的错误少3％。

##### URL
[http://arxiv.org/abs/1806.08205](http://arxiv.org/abs/1806.08205)

##### PDF
[http://arxiv.org/pdf/1806.08205](http://arxiv.org/pdf/1806.08205)

