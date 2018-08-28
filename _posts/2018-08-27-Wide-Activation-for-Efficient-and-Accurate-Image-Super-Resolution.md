---
layout: post
title: "Wide Activation for Efficient and Accurate Image Super-Resolution"
date: 2018-08-27 07:48:21
categories: arXiv_CV
tags: arXiv_CV Super_Resolution
author: Jiahui Yu, Yuchen Fan, Jianchao Yang, Ning Xu, Zhaowen Wang, Xinchao Wang, Thomas Huang
mathjax: true
---

* content
{:toc}

##### Abstract
In this report we demonstrate that with same parameters and computational budgets, models with wider features before ReLU activation have significantly better performance for single image super-resolution (SISR). The resulted SR residual network has a slim identity mapping pathway with wider (\(2\times\) to \(4\times\)) channels before activation in each residual block. To further widen activation (\(6\times\) to \(9\times\)) without computational overhead, we introduce linear low-rank convolution into SR networks and achieve even better accuracy-efficiency tradeoffs. In addition, compared with batch normalization or no normalization, we find training with weight normalization leads to better accuracy for deep super-resolution networks. Our proposed SR network \textit{WDSR} achieves better results on large-scale DIV2K image super-resolution benchmark in terms of PSNR with same or lower computational complexity. Based on WDSR, our method also won 1st places in NTIRE 2018 Challenge on Single Image Super-Resolution in all three realistic tracks. Experiments and ablation studies support the importance of wide activation for image super-resolution. Code is released at: https://github.com/JiahuiYu/wdsr_ntire2018

##### Abstract (translated by Google)
在本报告中，我们证明了使用相同的参数和计算预算，在ReLU激活之前具有更广泛特征的模型对于单图像超分辨率（SISR）具有明显更好的性能。产生的SR残余网络具有细长的身份映射路径，在每个残余块中激活之前具有更宽的（\（2 \倍）到\（4 \倍））信道。为了进一步扩展激活（\（6 \ times \）到\（9 \ times \））而没有计算开销，我们将线性低秩卷积引入SR网络，并实现更好的准确性 - 效率权衡。此外，与批量归一化或无归一化相比，我们发现权重归一化训练可以提高深度超分辨率网络的准确性。我们提出的SR网络\ textit {WDSR}在具有相同或更低计算复杂度的PSNR方面在大规模DIV2K图像超分辨率基准上获得了更好的结果。基于WDSR，我们的方法还在NTIRE 2018挑战中获得了所有三个真实轨道中单图像超分辨率的第一名。实验和消融研究支持广泛激活图像超分辨率的重要性。代码发布于：https：//github.com/JiahuiYu/wdsr_ntire2018

##### URL
[http://arxiv.org/abs/1808.08718](http://arxiv.org/abs/1808.08718)

##### PDF
[http://arxiv.org/pdf/1808.08718](http://arxiv.org/pdf/1808.08718)

