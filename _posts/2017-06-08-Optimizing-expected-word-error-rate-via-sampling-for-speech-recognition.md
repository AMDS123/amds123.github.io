---
layout: post
title: "Optimizing expected word error rate via sampling for speech recognition"
date: 2017-06-08 21:14:48
categories: arXiv_CL
tags: arXiv_CL GAN Speech_Recognition Optimization Classification Recognition
author: Matt Shannon
mathjax: true
---

* content
{:toc}

##### Abstract
State-level minimum Bayes risk (sMBR) training has become the de facto standard for sequence-level training of speech recognition acoustic models. It has an elegant formulation using the expectation semiring, and gives large improvements in word error rate (WER) over models trained solely using cross-entropy (CE) or connectionist temporal classification (CTC). sMBR training optimizes the expected number of frames at which the reference and hypothesized acoustic states differ. It may be preferable to optimize the expected WER, but WER does not interact well with the expectation semiring, and previous approaches based on computing expected WER exactly involve expanding the lattices used during training. In this paper we show how to perform optimization of the expected WER by sampling paths from the lattices used during conventional sMBR training. The gradient of the expected WER is itself an expectation, and so may be approximated using Monte Carlo sampling. We show experimentally that optimizing WER during acoustic model training gives 5% relative improvement in WER over a well-tuned sMBR baseline on a 2-channel query recognition task (Google Home).

##### Abstract (translated by Google)
国家级最低贝叶斯风险（sMBR）培训已成为语音识别声学模型序列级训练的事实标准。它具有使用期望半环的优雅公式，并且相对于仅使用交叉熵（CE）或连接主义时间分类（CTC）训练的模型，字错误率（WER）有很大改进。 sMBR训练优化了参考和假设声学状态不同的预期帧数。优化预期WER可能更好，但WER与预期半环不能很好地相互作用，以前基于计算预期WER的方法恰恰涉及扩展训练期间使用的格。在本文中，我们展示了如何通过从传统的sMBR训练中使用的格子采样路径来执行期望的WER的优化。预期的WER的梯度本身就是一个期望，所以可以用蒙特卡罗（Monte Carlo）抽样近似。我们通过实验显示，在声学模型训练期间优化WER，在双通道查询识别任务（Google Home）上，WER相对于良好调整的sMBR基线提高了5％。

##### URL
[https://arxiv.org/abs/1706.02776](https://arxiv.org/abs/1706.02776)

##### PDF
[https://arxiv.org/pdf/1706.02776](https://arxiv.org/pdf/1706.02776)

