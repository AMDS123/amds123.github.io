---
layout: post
title: "Non-local Low-rank Cube-based Tensor Factorization for Spectral CT Reconstruction"
date: 2018-07-24 14:15:03
categories: arXiv_CV
tags: arXiv_CV
author: Weiwen Wu, Fenglin Liu, Yanbo Zhang, Qian Wang, Hengyong Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Spectral computed tomography (CT) reconstructs material-dependent attenuation images with the projections of multiple narrow energy windows, it is meaningful for material identification and decomposition. Unfortunately, the multi-energy projection dataset always contains strong complicated noise and result in the projections has a lower signal-noise-ratio (SNR). Very recently, the spatial-spectral cube matching frame (SSCMF) was proposed to explore the non-local spatial-spectrum similarities for spectral CT. The method constructs such a group by clustering up a series of non-local spatial-spectrum cubes. The small size of spatial patch for such a group make SSCMF fails to encode the sparsity and low-rank properties. In addition, the hard-thresholding and collaboration filtering operation in the SSCMF are also rough to recover the image features and spatial edges. While for all steps are operated on 4-D group, we may not afford such huge computational and memory load in practical. To avoid the above limitation and further improve image quality, we first formulate a non-local cube-based tensor instead of the group to encode the sparsity and low-rank properties. Then, as a new regularizer, Kronecker-Basis-Representation (KBR) tensor factorization is employed into a basic spectral CT reconstruction model to enhance the ability of extracting image features and protecting spatial edges, generating the non-local low-rank cube-based tensor factorization (NLCTF) method. Finally, the split-Bregman strategy is adopted to solve the NLCTF model. Both numerical simulations and realistic preclinical mouse studies are performed to validate and assess the NLCTF algorithm. The results show that the NLCTF method outperforms the other competitors.

##### Abstract (translated by Google)
光谱计算机断层扫描（CT）利用多个窄能量窗的投影重建材料相关的衰减图像，这对于材料识别和分解是有意义的。不幸的是，多能量投影数据集总是包含强复杂的噪声并且导致投影具有较低的信噪比（SNR）。最近，提出了空间光谱立方体匹配框架（SSCMF）来探索光谱CT的非局部空间光谱相似性。该方法通过聚类一系列非局部空间谱立方体来构建这样的组。对于这样的组，小尺寸的空间补丁使得SSCMF无法编码稀疏性和低秩属性。此外，SSCMF中的硬阈值处理和协作过滤操作对于恢复图像特征和空间边缘也是粗略的。虽然所有步骤都是在4-D组上运行，但实际上我们可能无法承受如此巨大的计算和内存负载。为了避免上述限制并进一步提高图像质量，我们首先制定一个非局部的基于立方体的张量而不是该组来编码稀疏性和低秩性质。然后，作为一个新的正则化器，Kronecker-Basis-Representation（KBR）张量分解被用于基本光谱CT重建模型，以增强提取图像特征和保护空间边缘的能力，生成非局部低秩立方体张量因子分解（NLCTF）方法。最后，采用split-Bregman策略来解决NLCTF模型。进行数值模拟和现实的临床前小鼠研究以验证和评估NLCTF算法。结果表明，NLCTF方法优于其他竞争对手。

##### URL
[http://arxiv.org/abs/1807.10610](http://arxiv.org/abs/1807.10610)

##### PDF
[http://arxiv.org/pdf/1807.10610](http://arxiv.org/pdf/1807.10610)

