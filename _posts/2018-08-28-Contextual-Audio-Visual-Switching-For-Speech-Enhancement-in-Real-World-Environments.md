---
layout: post
title: "Contextual Audio-Visual Switching For Speech Enhancement in Real-World Environments"
date: 2018-08-28 17:27:11
categories: arXiv_CV
tags: arXiv_CV CNN
author: Ahsan Adeel, Mandar Gogate, Amir Hussain
mathjax: true
---

* content
{:toc}

##### Abstract
Human speech processing is inherently multimodal, where visual cues (lip movements) help to better understand the speech in noise. Lip-reading driven speech enhancement significantly outperforms benchmark audio-only approaches at low signal-to-noise ratios (SNRs). However, at high SNRs or low levels of background noise, visual cues become fairly less effective for speech enhancement. Therefore, a more optimal, context-aware audio-visual (AV) system is required, that contextually utilises both visual and noisy audio features and effectively accounts for different noisy conditions. In this paper, we introduce a novel contextual AV switching component that contextually exploits AV cues with respect to different operating conditions to estimate clean audio, without requiring any SNR estimation. The switching module switches between visual-only (V-only), audio-only (A-only), and both AV cues at low, high and moderate SNR levels, respectively. The contextual AV switching component is developed by integrating a convolutional neural network and long-short-term memory network. For testing, the estimated clean audio features are utilised by the developed novel enhanced visually derived Wiener filter for clean audio power spectrum estimation. The contextual AV speech enhancement method is evaluated under real-world scenarios using benchmark Grid and ChiME3 corpora. For objective testing, perceptual evaluation of speech quality is used to evaluate the quality of the restored speech. For subjective testing, the standard mean-opinion-score method is used. The critical analysis and comparative study demonstrate the outperformance of proposed contextual AV approach, over A-only, V-only, spectral subtraction, and log-minimum mean square error based speech enhancement methods at both low and high SNRs, revealing its capability to tackle spectro-temporal variation in any real-world noisy condition.

##### Abstract (translated by Google)
人类语音处理本质上是多模式的，其中视觉提示（嘴唇运动）有助于更好地理解噪声中的语音。唇读驱动语音增强在低信噪比（SNR）下明显优于基准音频方法。然而，在高SNR或低背景噪声水平下，视觉提示对于语音增强变得相当不太有效。因此，需要更优化的，上下文感知的视听（AV）系统，其在上下文中利用视觉和噪声音频特征并且有效地解决不同的噪声条件。在本文中，我们介绍了一种新颖的上下文AV切换组件，该组件在不需要任何SNR估计的情况下，根据不同的操作条件在上下文中利用AV提示来估计干净的音频。切换模块分别在低视野，高视野和中等SNR水平之间切换仅视觉（仅限V），仅音频（仅限A）和两个AV提示。通过集成卷积神经网络和长短期存储网络来开发上下文AV切换组件。为了测试，所开发的新颖增强的视觉导出的维纳滤波器利用估计的清洁音频特征来进行清洁的音频功率谱估计。使用基准Grid和ChiME3语料库在真实场景下评估上下文AV语音增强方法。对于客观测试，语音质量的感知评估用于评估恢复的语音的质量。对于主观测试，使用标准的均值 - 意见 - 得分方法。批判性分析和比较研究表明，在低信噪比和高信噪比下，基于仅A，仅V，频谱减法和基于对数最小均方误差的语音增强方法的所提出的上下文AV方法的优异性，揭示了其解决的能力在任何现实世界的噪声条件下的光谱 - 时间变化。

##### URL
[http://arxiv.org/abs/1808.09825](http://arxiv.org/abs/1808.09825)

##### PDF
[http://arxiv.org/pdf/1808.09825](http://arxiv.org/pdf/1808.09825)

