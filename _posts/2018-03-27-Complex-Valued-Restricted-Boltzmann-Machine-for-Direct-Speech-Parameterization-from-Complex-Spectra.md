---
layout: post
title: "Complex-Valued Restricted Boltzmann Machine for Direct Speech Parameterization from Complex Spectra"
date: 2018-03-27 08:07:20
categories: arXiv_SD
tags: arXiv_SD Classification Relation
author: Toru Nakashika, Shinji Takaki, Junichi Yamagishi
mathjax: true
---

* content
{:toc}

##### Abstract
This paper describes a novel energy-based probabilistic distribution that represents complex-valued data and explains how to apply it to direct feature extraction from complex-valued spectra. The proposed model, the complex-valued restricted Boltzmann machine (CRBM), is designed to deal with complex-valued visible units as an extension of the well-known restricted Boltzmann machine (RBM). Like the RBM, the CRBM learns the relationships between visible and hidden units without having connections between units in the same layer, which dramatically improves training efficiency by using Gibbs sampling or contrastive divergence (CD). Another important characteristic is that the CRBM also has connections between real and imaginary parts of each of the complex-valued visible units that help represent the data distribution in the complex domain. In speech signal processing, classification and generation features are often based on amplitude spectra (e.g., MFCC, cepstra, and mel-cepstra) even if they are calculated from complex spectra, and they ignore phase information. In contrast, the proposed feature extractor using the CRBM directly encodes the complex spectra (or another complex-valued representation of the complex spectra) into binary-valued latent features (hidden units). Since the visible-hidden connections are undirected, we can also recover (decode) the complex spectra from the latent features directly. Our speech coding experiments demonstrated that the CRBM outperformed other speech coding methods, such as methods using the conventional RBM, the mel-log spectrum approximate (MLSA) decoder, etc.

##### Abstract (translated by Google)
本文描述了一种新颖的基于能量的概率分布，表示复数值数据并解释如何将其应用于从复数值谱中直接提取特征。所提出的模型，即复数限制玻尔兹曼机（CRBM），被设计用于处理复数值可见单元，作为众所周知的限制玻尔兹曼机（RBM）的延伸。和RBM一样，CRBM学习可见和隐藏单元之间的关系，而不需要在同一层单元之间建立联系，这通过使用Gibbs抽样或对比散度（CD）显着提高了训练效率。另一个重要特征是CRBM还在每个复数值可见单元的实数部分和虚数部分之间建立联系，这些部分有助于表示复数域中的数据分布。在语音信号处理中，分类和生成特征通常基于幅度谱（即，MFCC，cepstra和mel-cepstra），即使它们是从复杂谱图计算的，并且它们忽略相位信息。相反，所提出的使用CRBM的特征提取器直接将复谱（或复谱的另一个复值表示）编码为二值的潜在特征（隐藏单元）。由于可见隐藏连接是无向的，因此我们也可以直接恢复（解码）来自潜在特征的复杂光谱。我们的语音编码实验表明，CRBM优于其他语音编码方法，例如使用传统RBM，mel-log频谱近似（MLSA）解码器等的方法。

##### URL
[https://arxiv.org/abs/1803.09946](https://arxiv.org/abs/1803.09946)

##### PDF
[https://arxiv.org/pdf/1803.09946](https://arxiv.org/pdf/1803.09946)

