---
layout: post
title: "Wave-U-Net: A Multi-Scale Neural Network for End-to-End Audio Source Separation"
date: 2018-06-08 14:29:08
categories: arXiv_SD
tags: arXiv_SD Prediction Relation
author: Daniel Stoller, Sebastian Ewert, Simon Dixon
mathjax: true
---

* content
{:toc}

##### Abstract
Models for audio source separation usually operate on the magnitude spectrum, which ignores phase information and makes separation performance dependant on hyper-parameters for the spectral front-end. Therefore, we investigate end-to-end source separation in the time-domain, which allows modelling phase information and avoids fixed spectral transformations. Due to high sampling rates for audio, employing a long temporal input context on the sample level is difficult, but required for high quality separation results because of long-range temporal correlations. In this context, we propose the Wave-U-Net, an adaptation of the U-Net to the one-dimensional time domain, which repeatedly resamples feature maps to compute and combine features at different time scales. We introduce further architectural improvements, including an output layer that enforces source additivity, an upsampling technique and a context-aware prediction framework to reduce output artifacts. Experiments for singing voice separation indicate that our architecture yields a performance comparable to a state-of-the-art spectrogram-based U-Net architecture, given the same data. Finally, we reveal a problem with outliers in the currently used SDR evaluation metrics and suggest reporting rank-based statistics to alleviate this problem.

##### Abstract (translated by Google)
音频源分离模型通常在幅度谱上运行，忽略相位信息，并使分离性能取决于谱前端的超参数。因此，我们研究时域中的端到端信号源分离，这可以建模相位信息并避免固定的频谱变换。由于音频采样率较高，因此在采样级采用长时间输入上下文很困难，但由于长距离时间相关性而需要高质量分离结果。在这种情况下，我们提出了Wave-U-Net，这是U-Net到一维时域的改编，它反复重新采样特征地图以在不同时间尺度上计算和合并特征。我们介绍进一步的体系结构改进，包括强制实施源可加性的输出层，上采样技术和上下文感知预测框架以减少输出伪像。对于歌唱语音分离的实验表明，我们的架构产生的性能堪比基于最先进的基于频谱图的U-Net架构，只要数据相同。最后，我们揭示了当前使用的SDR评估指标中存在异常值的问题，并建议报告基于等级的统计数据以缓解此问题。

##### URL
[http://arxiv.org/abs/1806.03185](http://arxiv.org/abs/1806.03185)

##### PDF
[http://arxiv.org/pdf/1806.03185](http://arxiv.org/pdf/1806.03185)

