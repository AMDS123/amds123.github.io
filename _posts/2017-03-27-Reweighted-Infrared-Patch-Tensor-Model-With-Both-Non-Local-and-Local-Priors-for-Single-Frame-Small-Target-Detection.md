---
layout: post
title: "Reweighted Infrared Patch-Tensor Model With Both Non-Local and Local Priors for Single-Frame Small Target Detection"
date: 2017-03-27 15:57:27
categories: arXiv_CV
tags: arXiv_CV Sparse Detection Relation
author: Yimian Dai, Yiquan Wu
mathjax: true
---

* content
{:toc}

##### Abstract
Many state-of-the-art methods have been proposed for infrared small target detection. They work well on the images with homogeneous backgrounds and high-contrast targets. However, when facing highly heterogeneous backgrounds, they would not perform very well, mainly due to: 1) the existence of strong edges and other interfering components, 2) not utilizing the priors fully. Inspired by this, we propose a novel method to exploit both local and non-local priors simultaneously. Firstly, we employ a new infrared patch-tensor (IPT) model to represent the image and preserve its spatial correlations. Exploiting the target sparse prior and background non-local self-correlation prior, the target-background separation is modeled as a robust low-rank tensor recovery problem. Moreover, with the help of the structure tensor and reweighted idea, we design an entry-wise local-structure-adaptive and sparsity enhancing weight to replace the globally constant weighting parameter. The decomposition could be achieved via the element-wise reweighted higher-order robust principal component analysis with an additional convergence condition according to the practical situation of target detection. Extensive experiments demonstrate that our model outperforms the other state-of-the-arts, in particular for the images with very dim targets and heavy clutters.

##### Abstract (translated by Google)
已经提出了许多用于红外小目标检测的最新方法。他们在背景均匀，对比度高的图像上工作得很好。但是，面对高度异质的背景时，表现不佳，主要是由于：1）边缘强等干扰成分的存在，2）不充分利用先验。受此启发，我们提出了一种同时利用本地和非本地先辈的新方法。首先，我们采用一种新的红外斑块张量（IPT）模型来表示图像并保持其空间相关性。利用目标稀疏先验和背景非局部自相关之前，目标背景分离建模为一个鲁棒的低秩张量恢复问题。此外，在结构张量和重新加权的思想的帮助下，设计了一个基于入口的局部结构自适应和稀疏增强权重来代替全局恒定的权重参数。根据目标检测的实际情况，可以通过单元重加权的高阶鲁棒主分量分析和附加的收敛条件来实现分解。大量的实验表明，我们的模型胜过了其他的艺术，特别是对于目标很暗，杂乱无章的图像。

##### URL
[https://arxiv.org/abs/1703.09157](https://arxiv.org/abs/1703.09157)

##### PDF
[https://arxiv.org/pdf/1703.09157](https://arxiv.org/pdf/1703.09157)

