---
layout: post
title: "Automatic Quality Estimation for ASR System Combination"
date: 2017-06-22 10:11:34
categories: arXiv_CL
tags: arXiv_CL Knowledge Speech_Recognition Recognition
author: Shahab Jalalvand, Matteo Negri, Daniele Falavigna, Marco Matassoni, Marco Turchi
mathjax: true
---

* content
{:toc}

##### Abstract
Recognizer Output Voting Error Reduction (ROVER) has been widely used for system combination in automatic speech recognition (ASR). In order to select the most appropriate words to insert at each position in the output transcriptions, some ROVER extensions rely on critical information such as confidence scores and other ASR decoder features. This information, which is not always available, highly depends on the decoding process and sometimes tends to over estimate the real quality of the recognized words. In this paper we propose a novel variant of ROVER that takes advantage of ASR quality estimation (QE) for ranking the transcriptions at "segment level" instead of: i) relying on confidence scores, or ii) feeding ROVER with randomly ordered hypotheses. We first introduce an effective set of features to compensate for the absence of ASR decoder information. Then, we apply QE techniques to perform accurate hypothesis ranking at segment-level before starting the fusion process. The evaluation is carried out on two different tasks, in which we respectively combine hypotheses coming from independent ASR systems and multi-microphone recordings. In both tasks, it is assumed that the ASR decoder information is not available. The proposed approach significantly outperforms standard ROVER and it is competitive with two strong oracles that e xploit prior knowledge about the real quality of the hypotheses to be combined. Compared to standard ROVER, the abs olute WER improvements in the two evaluation scenarios range from 0.5% to 7.3%.

##### Abstract (translated by Google)
识别器输出投票错误减少（ROVER）已被广泛用于自动语音识别（ASR）中的系统组合。为了选择最合适的单词插入输出转录的每个位置，一些ROVER扩展依赖于关键信息，如置信度分数和其他ASR解码器功能。这种并不总是可用的信息在很大程度上取决于解码过程，有时倾向于高估被识别单词的真实质量。在本文中，我们提出了一种新的ROVER变体，它利用ASR质量估计（QE）对“片段级”的转录进行排序，而不是：i）依靠置信度得分，或者ii）向ROVER提供随机排序的假设。我们首先引入一组有效的功能来弥补ASR解码器信息的缺失。然后，在开始融合过程之前，我们应用QE技术在片段级别上进行精确的假设排序。评估是在两个不同的任务上进行的，其中我们分别将来自独立ASR系统的假设与多麦克风录音相结合。在这两个任务中，假定ASR解码器信息不可用。所提出的方法明显优于标准ROVER，并且与两个强大的预言竞争，这两个预言知道关于假设的真实质量的先验知识。与标准ROVER相比，两种评估方案的绝对WER改进范围为0.5％至7.3％。

##### URL
[https://arxiv.org/abs/1706.07238](https://arxiv.org/abs/1706.07238)

##### PDF
[https://arxiv.org/pdf/1706.07238](https://arxiv.org/pdf/1706.07238)

