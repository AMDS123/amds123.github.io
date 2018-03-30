---
layout: post
title: "Spectral feature mapping with mimic loss for robust speech recognition"
date: 2018-03-26 19:56:21
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Recognition
author: Deblin Bagchi, Peter Plantinga, Adam Stiff, Eric Fosler-Lussier
mathjax: true
---

* content
{:toc}

##### Abstract
For the task of speech enhancement, local learning objectives are agnostic to phonetic structures helpful for speech recognition. We propose to add a global criterion to ensure de-noised speech is useful for downstream tasks like ASR. We first train a spectral classifier on clean speech to predict senone labels. Then, the spectral classifier is joined with our speech enhancer as a noisy speech recognizer. This model is taught to imitate the output of the spectral classifier alone on clean speech. This \textit{mimic loss} is combined with the traditional local criterion to train the speech enhancer to produce de-noised speech. Feeding the de-noised speech to an off-the-shelf Kaldi training recipe for the CHiME-2 corpus shows significant improvements in WER.

##### Abstract (translated by Google)
对于语音增强的任务，本地学习目标对于语音识别有用的语音结构是不可知的。我们建议添加一个全球标准，以确保去噪语音对ASR等下行任务非常有用。我们首先训练一个干净的语音频谱分类器来预测语音标签。然后，谱分类器与我们的语音增强器一起作为噪声语音识别器加入。这个模型被教导来模仿纯粹语音中光谱分类器的输出。这个\ textit {mimic loss}与传统的本地标准相结合来训练语音增强器产生去噪语音。将去噪语音提供给CHiME-2语料库的现成Kaldi训练配方，显示了WER的显着改进。

##### URL
[https://arxiv.org/abs/1803.09816](https://arxiv.org/abs/1803.09816)

##### PDF
[https://arxiv.org/pdf/1803.09816](https://arxiv.org/pdf/1803.09816)

