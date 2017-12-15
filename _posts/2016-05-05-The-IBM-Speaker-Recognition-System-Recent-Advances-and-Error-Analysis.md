---
layout: post
title: "The IBM Speaker Recognition System: Recent Advances and Error Analysis"
date: 2016-05-05 15:57:21
categories: arXiv_CL
tags: arXiv_CL Knowledge Speech_Recognition Recognition
author: Seyed Omid Sadjadi, Jason Pelecanos, Sriram Ganapathy
mathjax: true
---

* content
{:toc}

##### Abstract
We present the recent advances along with an error analysis of the IBM speaker recognition system for conversational speech. Some of the key advancements that contribute to our system include: a nearest-neighbor discriminant analysis (NDA) approach (as opposed to LDA) for intersession variability compensation in the i-vector space, the application of speaker and channel-adapted features derived from an automatic speech recognition (ASR) system for speaker recognition, and the use of a DNN acoustic model with a very large number of output units (~10k senones) to compute the frame-level soft alignments required in the i-vector estimation process. We evaluate these techniques on the NIST 2010 SRE extended core conditions (C1-C9), as well as the 10sec-10sec condition. To our knowledge, results achieved by our system represent the best performances published to date on these conditions. For example, on the extended tel-tel condition (C5) the system achieves an EER of 0.59%. To garner further understanding of the remaining errors (on C5), we examine the recordings associated with the low scoring target trials, where various issues are identified for the problematic recordings/trials. Interestingly, it is observed that correcting the pathological recordings not only improves the scores for the target trials but also for the nontarget trials.

##### Abstract (translated by Google)
我们介绍了最近的进展，以及针对对话语音的IBM说话人识别系统的错误分析。一些对我们系统有贡献的重要进展包括：i-向量空间中的间隔变化补偿的最近邻判别分析（NDA）方法（相对于LDA），来自用于说话人识别的自动语音识别（ASR）系统，以及使用具有大量输出单元（〜10k个语音）的DNN声学模型来计算i矢量估计过程中所需的帧级软对准。我们在NIST 2010 SRE扩展核心条件（C1-C9）以及10sec-10sec条件下评估这些技术。据我们所知，我们的系统取得的成果代表了迄今为止在这些条件下发布的最佳表现。例如，在扩展电话条件（C5）下，系统达到0.59％的EER。为了进一步了解其余的错误（C5），我们检查与低分计划目标试验相关的记录，其中记录/试验的各种问题被确定。有趣的是，观察到纠正病理记录不仅提高了目标试验的分数，而且也提高了非目标试验的分数。

##### URL
[https://arxiv.org/abs/1605.01635](https://arxiv.org/abs/1605.01635)

##### PDF
[https://arxiv.org/pdf/1605.01635](https://arxiv.org/pdf/1605.01635)

