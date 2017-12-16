---
layout: post
title: "Bit-pragmatic Deep Neural Network Computing"
date: 2016-10-20 22:16:05
categories: arXiv_CV
tags: arXiv_CV CNN
author: J. Albericio, P. Judd, A. Delmás, S. Sharify, A. Moshovos
mathjax: true
---

* content
{:toc}

##### Abstract
We quantify a source of ineffectual computations when processing the multiplications of the convolutional layers in Deep Neural Networks (DNNs) and propose Pragmatic (PRA), an architecture that exploits it improving performance and energy efficiency. The source of these ineffectual computations is best understood in the context of conventional multipliers which generate internally multiple terms, that is, products of the multiplicand and powers of two, which added together produce the final product [1]. At runtime, many of these terms are zero as they are generated when the multiplicand is combined with the zero-bits of the multiplicator. While conventional bit-parallel multipliers calculate all terms in parallel to reduce individual product latency, PRA calculates only the non-zero terms using a) on-the-fly conversion of the multiplicator representation into an explicit list of powers of two, and b) hybrid bit-parallel multplicand/bit-serial multiplicator processing units. PRA exploits two sources of ineffectual computations: 1) the aforementioned zero product terms which are the result of the lack of explicitness in the multiplicator representation, and 2) the excess in the representation precision used for both multiplicants and multiplicators, e.g., [2]. Measurements demonstrate that for the convolutional layers, a straightforward variant of PRA improves performance by 2.6x over the DaDiaNao (DaDN) accelerator [3] and by 1.4x over STR [4]. Similarly, PRA improves energy efficiency by 28% and 10% on average compared to DaDN and STR. An improved cross lane synchronication scheme boosts performance improvements to 3.1x over DaDN. Finally, Pragmatic benefits persist even with an 8-bit quantized representation [5].

##### Abstract (translated by Google)
我们在处理深度神经网络（DNNs）中的卷积层的乘法时量化无效计算的来源，并提出实用（PRA），一种利用其提高性能和能量效率的架构。这些无效计算的来源是在传统的内部产生多个项的乘法器的情况下得到最好的理解，即被乘数和两个乘方的乘积产生最终的乘积[1]。在运行时，许多这些项是零，因为它们是在被乘数与乘数的零位组合时产生的。虽然传统的位并行乘法器并行计算所有项以减少个别产品延迟，但PRA仅使用a）将乘数表达式即时转换为2的幂的显式列表来计算非零项，以及b）混合比特并行的多比特/比特串行乘法器处理单元。 PRA利用了无效计算的两个来源：1）上述零乘积项是乘数表达式中缺乏显式性的结果; 2）用于乘数和乘数的表示精度的过量，例如[2] 。测量表明，对于卷积层，一个简单的PRA变体比DaDiaNao（DaDN）加速器性能提高了2.6倍[3]，比STR提高了1.4倍[4]。同样，与DaDN和STR相比，PRA的能源效率平均提高了28％和10％。改进的交叉车道同步方案将性能提高至DaDN的3.1倍。最后，即使是8位量化表示，语用效益也会持续下去[5]。

##### URL
[https://arxiv.org/abs/1610.06920](https://arxiv.org/abs/1610.06920)

##### PDF
[https://arxiv.org/pdf/1610.06920](https://arxiv.org/pdf/1610.06920)

