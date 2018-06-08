---
layout: post
title: "Domain Adversarial Training for Accented Speech Recognition"
date: 2018-06-07 17:02:54
categories: arXiv_CL
tags: arXiv_CL Adversarial Speech_Recognition Recognition
author: Sining Sun, Ching-Feng Yeh, Mei-Yuh Hwang, Mari Ostendorf, Lei Xie
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a domain adversarial training (DAT) algorithm to alleviate the accented speech recognition problem. In order to reduce the mismatch between labeled source domain data ("standard" accent) and unlabeled target domain data (with heavy accents), we augment the learning objective for a Kaldi TDNN network with a domain adversarial training (DAT) objective to encourage the model to learn accent-invariant features. In experiments with three Mandarin accents, we show that DAT yields up to 7.45% relative character error rate reduction when we do not have transcriptions of the accented speech, compared with the baseline trained on standard accent data only. We also find a benefit from DAT when used in combination with training from automatic transcriptions on the accented data. Furthermore, we find that DAT is superior to multi-task learning for accented speech recognition.

##### Abstract (translated by Google)
在本文中，我们提出了一个领域对抗训练（DAT）算法来缓解重音语音识别问题。为了减少标记的源域数据（“标准”重音）与未标记的目标域数据（具有重音调）之间的不匹配，我们增强了具有域对抗训练（DAT）目标的Kaldi TDNN网络的学习目标，以鼓励模型来学习重音不变的特征。在使用三种普通话口音的实验中，我们表明，与仅在标准口音数据上训练的基线相比，当我们没有口音语音的转录时，DAT的相对字符错误率降低高达7.45％。当与重音数据上的自动转录训练结合使用时，我们也从DAT中获益。此外，我们发现DAT优于用于重音语音识别的多任务学习。

##### URL
[http://arxiv.org/abs/1806.02786](http://arxiv.org/abs/1806.02786)

##### PDF
[http://arxiv.org/pdf/1806.02786](http://arxiv.org/pdf/1806.02786)

