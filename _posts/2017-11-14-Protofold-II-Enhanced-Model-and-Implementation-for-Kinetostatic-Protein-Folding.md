---
layout: post
title: "Protofold II: Enhanced Model and Implementation for Kinetostatic Protein Folding"
date: 2017-11-14 11:36:29
categories: arXiv_RO
tags: arXiv_RO Face Prediction
author: Pouya Tavousi, Morad Behandish, Horea T. Ilies, Kazem Kazerounian
mathjax: true
---

* content
{:toc}

##### Abstract
A reliable prediction of 3D protein structures from sequence data remains a big challenge due to both theoretical and computational difficulties. We have previously shown that our kinetostatic compliance method (KCM) implemented into the Protofold package can overcome some of the key difficulties faced by other de novo structure prediction methods, such as the very small time steps required by the molecular dynamics (MD) approaches or the very large number of samples needed by the Monte Carlo (MC) sampling techniques. In this article, we improve the free energy formulation used in Protofold by including the typically underrated entropic effects, imparted due to differences in hydrophobicity of the chemical groups, which dominate the folding of most water-soluble proteins. In addition to the model enhancement, we revisit the numerical implementation by redesigning the algorithms and introducing efficient data structures that reduce the expected complexity from quadratic to linear. Moreover, we develop and optimize parallel implementations of the algorithms on both central and graphics processing units (CPU/GPU) achieving speed-ups up to two orders of magnitude on the GPU. Our simulations are consistent with the general behavior observed in the folding process in aqueous solvent, confirming the effectiveness of model improvements. We report on the folding process at multiple levels; namely, the formation of secondary structural elements and tertiary interactions between secondary elements or across larger domains. We also observe significant enhancements in running times that make the folding simulation tractable for large molecules.

##### Abstract (translated by Google)
由于理论和计算困难，从序列数据可靠地预测3D蛋白质结构仍然是一个巨大的挑战。我们之前已经表明，我们在Protofold软件包中实现的动力学静脉顺应性方法（KCM）可以克服其他从头结构预测方法面临的一些关键困难，例如分子动力学（MD）方法所需的非常小的时间步骤或蒙特卡洛（MC）采样技术所需要的非常大量的样本。在这篇文章中，我们改进了Protofold中使用的自由能公式，通过包括典型的被低估的熵效应，由于化学基团疏水性的差异而赋予了主导大多数水溶性蛋白质折叠的熵效应。除了模型增强之外，我们通过重新设计算法并引入高效的数据结构来重新审视数值实现，从而将预期的复杂性从二次型降低到线性。此外，我们在中央处理器和图形处理器（CPU / GPU）上开发和优化算法的并行实现，在GPU上实现高达两个数量级的加速。我们的模拟与在含水溶剂中折叠过程中观察到的一般行为一致，证实模型改进的有效性。我们报告多层次的折叠过程;即二级结构元素的形成和二级元素之间或跨越较大结构域的三级相互作用。我们还观察到运行时间的显着增强，使折叠模拟易于处理大分子。

##### URL
[http://arxiv.org/abs/1712.05012](http://arxiv.org/abs/1712.05012)

##### PDF
[http://arxiv.org/pdf/1712.05012](http://arxiv.org/pdf/1712.05012)

