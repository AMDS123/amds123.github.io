---
layout: post
title: "Learning Deep Convolutional Networks for Demosaicing"
date: 2018-02-11 16:57:50
categories: arXiv_CV
tags: arXiv_CV CNN Optimization
author: Nai-Sheng Syu, Yu-Sheng Chen, Yung-Yu Chuang
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a comprehensive study of applying the convolutional neural network (CNN) to solving the demosaicing problem. The paper presents two CNN models that learn end-to-end mappings between the mosaic samples and the original image patches with full information. In the case the Bayer color filter array (CFA) is used, an evaluation with ten competitive methods on popular benchmarks confirms that the data-driven, automatically learned features by the CNN models are very effective. Experiments show that the proposed CNN models can perform equally well in both the sRGB space and the linear space. It is also demonstrated that the CNN model can perform joint denoising and demosaicing. The CNN model is very flexible and can be easily adopted for demosaicing with any CFA design. We train CNN models for demosaicing with three different CFAs and obtain better results than existing methods. With the great flexibility to be coupled with any CFA, we present the first data-driven joint optimization of the CFA design and the demosaicing method using CNN. Experiments show that the combination of the automatically discovered CFA pattern and the automatically devised demosaicing method significantly outperforms the current best demosaicing results. Visual comparisons confirm that the proposed methods reduce more visual artifacts than existing methods. Finally, we show that the CNN model is also effective for the more general demosaicing problem with spatially varying exposure and color and can be used for taking images of higher dynamic ranges with a single shot. The proposed models and the thorough experiments together demonstrate that CNN is an effective and versatile tool for solving the demosaicing problem.

##### Abstract (translated by Google)
本文提出了应用卷积神经网络（CNN）解决去马赛克问题的综合研究。本文介绍了两种CNN模型，可以学习镶嵌样本与具有完整信息的原始图像补丁之间的端到端映射。在使用拜耳滤色镜阵列（CFA）的情况下，在流行基准测试中采用十种竞争方法进行评估，证实CNN模型的数据驱动的自动学习功能非常有效。实验表明，提出的CNN模型在sRGB空间和线性空间中都可以表现出同样的效果。还证明了CNN模型可以执行联合去噪和去马赛克。 CNN模型非常灵活，可以很容易地采用任何CFA设计进行去马赛克。我们使用三种不同的CFA对CNN模型进行去马赛克培训，并获得比现有方法更好的结果。凭借与任何CFA结合的巨大灵活性，我们提出了首次使用CNN的CFA设计和去马赛克方法的数据驱动联合优化。实验表明，自动发现的CFA模式和自动设计的去马赛克方法的组合显着优于当前最好的去马赛克结果。视觉比较证实，所提出的方法减少了比现有方法更多的视觉伪影。最后，我们证明了CNN模型对于具有空间变化的曝光和颜色的更一般的去马赛克问题也是有效的，并且可以用于单次拍摄更高动态范围的图像。所提出的模型和彻底的实验一起证明CNN是解决去马赛克问题的有效和多用途的工具。

##### URL
[http://arxiv.org/abs/1802.03769](http://arxiv.org/abs/1802.03769)

##### PDF
[http://arxiv.org/pdf/1802.03769](http://arxiv.org/pdf/1802.03769)

