---
layout: post
title: "Estimation of Tissue Microstructure Using a Deep Network Inspired by a Sparse Reconstruction Framework"
date: 2017-04-05 02:37:44
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Chuyang Ye
mathjax: true
---

* content
{:toc}

##### Abstract
Diffusion magnetic resonance imaging (dMRI) provides a unique tool for noninvasively probing the microstructure of the neuronal tissue. The NODDI model has been a popular approach to the estimation of tissue microstructure in many neuroscience studies. It represents the diffusion signals with three types of diffusion in tissue: intra-cellular, extra-cellular, and cerebrospinal fluid compartments. However, the original NODDI method uses a computationally expensive procedure to fit the model and could require a large number of diffusion gradients for accurate microstructure estimation, which may be impractical for clinical use. Therefore, efforts have been devoted to efficient and accurate NODDI microstructure estimation with a reduced number of diffusion gradients. In this work, we propose a deep network based approach to the NODDI microstructure estimation, which is named Microstructure Estimation using a Deep Network (MEDN). Motivated by the AMICO algorithm which accelerates the computation of NODDI parameters, we formulate the microstructure estimation problem in a dictionary-based framework. The proposed network comprises two cascaded stages. The first stage resembles the solution to a dictionary-based sparse reconstruction problem and the second stage computes the final microstructure using the output of the first stage. The weights in the two stages are jointly learned from training data, which is obtained from training dMRI scans with diffusion gradients that densely sample the q-space. The proposed method was applied to brain dMRI scans, where two shells each with 30 gradient directions (60 diffusion gradients in total) were used. Estimation accuracy with respect to the gold standard was measured and the results demonstrate that MEDN outperforms the competing algorithms.

##### Abstract (translated by Google)
扩散磁共振成像（dMRI）为无创探查神经组织的微观结构提供了独特的工具。在许多神经科学研究中，NODDI模型一直是估计组织微观结构的流行方法。它表示在组织中有三种扩散的扩散信号：细胞内，细胞外和脑脊液隔室。然而，原始的NODDI方法使用计算上昂贵的过程来拟合模型，并且可能需要大量的扩散梯度来进行准确的微观结构估计，这在临床应用中可能是不切实际的。因此，努力致力于以减少的扩散梯度数量来高效且准确地进行NODDI微观结构估计。在这项工作中，我们提出了一种基于深度网络的方法来进行NODDI微观结构估计，即使用深度网络（MEDN）进行微观结构估计。在加速NODDI参数计算的AMICO算法的推动下，我们在基于字典的框架下制定了微观结构估计问题。提出的网络包含两个级联级。第一阶段类似于基于字典的稀疏重建问题的解决方案，第二阶段使用第一阶段的输出来计算最终的微观结构。这两个阶段的权重是从训练数据联合学习的，训练数据是从训练dMRI扫描获得的密集样本的q-空间的扩散梯度。所提出的方法应用于脑部dMRI扫描，其中使用两个各具有30个梯度方向（总共60个扩散梯度）的壳。对黄金标准的估计精度进行了测量，结果表明MEDN优于竞争算法。

##### URL
[https://arxiv.org/abs/1704.01246](https://arxiv.org/abs/1704.01246)

##### PDF
[https://arxiv.org/pdf/1704.01246](https://arxiv.org/pdf/1704.01246)

