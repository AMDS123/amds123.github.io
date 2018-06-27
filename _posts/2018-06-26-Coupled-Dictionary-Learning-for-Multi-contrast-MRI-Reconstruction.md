---
layout: post
title: "Coupled Dictionary Learning for Multi-contrast MRI Reconstruction"
date: 2018-06-26 11:52:57
categories: arXiv_CV
tags: arXiv_CV Sparse Relation
author: Pingfan Song, Lior Weizman, Joao F.C. Mota, Yonina C. Eldar, Miguel R.D. Rodrigues
mathjax: true
---

* content
{:toc}

##### Abstract
Medical imaging tasks often involve multiple contrasts, such as T1- and T2-weighted magnetic resonance imaging (MRI) data. These contrasts capture information associated with the same underlying anatomy and thus exhibit similarities. In this paper, we propose a Coupled Dictionary Learning based multi-contrast MRI reconstruction (CDLMRI) approach to leverage an available guidance contrast to restore the target contrast. Our approach consists of three stages: coupled dictionary learning, coupled sparse denoising, and $k$-space consistency enforcing. The first stage learns a group of dictionaries that capture correlations among multiple contrasts. By capitalizing on the learned adaptive dictionaries, the second stage performs joint sparse coding to denoise the corrupted target image with the aid of a guidance contrast. The third stage enforces consistency between the denoised image and the measurements in the $k$-space domain. Numerical experiments on the retrospective under-sampling of clinical MR images demonstrate that incorporating additional guidance contrast via our design improves MRI reconstruction, compared to state-of-the-art approaches.

##### Abstract (translated by Google)
医学成像任务通常涉及多种对比度，如T1和T2加权磁共振成像（MRI）数据。这些对比捕捉与相同底层解剖结构相关的信息，并因此表现出相似性。在本文中，我们提出了一种基于耦合字典学习的多对比MRI重建（CDLMRI）方法，以利用可用的指导对比度来恢复目标对比度。我们的方法由三个阶段组成：耦合字典学习，耦合稀疏去噪和$ k $  - 空间一致性实施。第一阶段学习一组能够捕捉多种对比之间相关性的词典。通过利用已学习的自适应字典，第二阶段执行联合稀疏编码以借助于引导对比度对已损坏的目标图像进行去噪。第三阶段强制降噪图像与$ k $ -space域中的度量值之间的一致性。对临床MR图像进行回顾性欠采样的数值实验表明，与最先进的方法相比，通过我们的设计合并额外的引导对比改善了MRI重建。

##### URL
[http://arxiv.org/abs/1806.09930](http://arxiv.org/abs/1806.09930)

##### PDF
[http://arxiv.org/pdf/1806.09930](http://arxiv.org/pdf/1806.09930)

