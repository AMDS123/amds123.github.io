---
layout: post
title: "Uncertainty in multitask learning: joint representations for probabilistic MR-only radiotherapy planning"
date: 2018-06-18 10:56:12
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN Inference
author: Felix J.S. Bragman, Ryutaro Tanno, Zach Eaton-Rosen, Wenqi Li, David J. Hawkes, Sebastien Ourselin, Daniel C. Alexander, Jamie R. McClelland, M. Jorge Cardoso
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-task neural network architectures provide a mechanism that jointly integrates information from distinct sources. It is ideal in the context of MR-only radiotherapy planning as it can jointly regress a synthetic CT (synCT) scan and segment organs-at-risk (OAR) from MRI. We propose a probabilistic multi-task network that estimates: 1) intrinsic uncertainty through a heteroscedastic noise model for spatially-adaptive task loss weighting and 2) parameter uncertainty through approximate Bayesian inference. This allows sampling of multiple segmentations and synCTs that share their network representation. We test our model on prostate cancer scans and show that it produces more accurate and consistent synCTs with a better estimation in the variance of the errors, state of the art results in OAR segmentation and a methodology for quality assurance in radiotherapy treatment planning.

##### Abstract (translated by Google)
多任务神经网络体系结构提供了一种机制，可共同整合来自不同来源的信息。在MR-only放疗计划的背景下，它是理想的，因为它可以共同对来自MRI的合成CT（synCT）扫描和分割器官风险（OAR）进行回归。我们提出了一个概率多任务网络，其估计：1）通过异步噪声模型的空间自适应任务损失加权的内在不确定性;以及2）通过近似贝叶斯推断的参数不确定性。这允许采样共享其网络表示的多个分段和同步。我们测试了我们的前列腺癌扫描模型，并证明它可以产生更准确和一致的synCTs，并具有更好的误差方差估计，OAR分割的最新技术结果以及放射治疗计划中的质量保证方法。

##### URL
[http://arxiv.org/abs/1806.06595](http://arxiv.org/abs/1806.06595)

##### PDF
[http://arxiv.org/pdf/1806.06595](http://arxiv.org/pdf/1806.06595)

