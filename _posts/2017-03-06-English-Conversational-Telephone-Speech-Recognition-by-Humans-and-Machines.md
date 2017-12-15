---
layout: post
title: "English Conversational Telephone Speech Recognition by Humans and Machines"
date: 2017-03-06 22:37:43
categories: arXiv_SD
tags: arXiv_SD Adversarial Speech_Recognition CNN RNN Deep_Learning Language_Model Recognition
author: George Saon, Gakuto Kurata, Tom Sercu, Kartik Audhkhasi, Samuel Thomas, Dimitrios Dimitriadis, Xiaodong Cui, Bhuvana Ramabhadran, Michael Picheny, Lynn-Li Lim, Bergul Roomi, Phil Hall
mathjax: true
---

* content
{:toc}

##### Abstract
One of the most difficult speech recognition tasks is accurate recognition of human to human communication. Advances in deep learning over the last few years have produced major speech recognition improvements on the representative Switchboard conversational corpus. Word error rates that just a few years ago were 14% have dropped to 8.0%, then 6.6% and most recently 5.8%, and are now believed to be within striking range of human performance. This then raises two issues - what IS human performance, and how far down can we still drive speech recognition error rates? A recent paper by Microsoft suggests that we have already achieved human performance. In trying to verify this statement, we performed an independent set of human performance measurements on two conversational tasks and found that human performance may be considerably better than what was earlier reported, giving the community a significantly harder goal to achieve. We also report on our own efforts in this area, presenting a set of acoustic and language modeling techniques that lowered the word error rate of our own English conversational telephone LVCSR system to the level of 5.5%/10.3% on the Switchboard/CallHome subsets of the Hub5 2000 evaluation, which - at least at the writing of this paper - is a new performance milestone (albeit not at what we measure to be human performance!). On the acoustic side, we use a score fusion of three models: one LSTM with multiple feature inputs, a second LSTM trained with speaker-adversarial multi-task learning and a third residual net (ResNet) with 25 convolutional layers and time-dilated convolutions. On the language modeling side, we use word and character LSTMs and convolutional WaveNet-style language models.

##### Abstract (translated by Google)
其中一个最困难的语音识别任务是准确识别人与人之间的沟通。在过去几年的深入学习的进展已经产生了重要的语音识别改进代表交换机对话语料库。几年前，14％的字错误率下降到8.0％，然后是6.6％，最近5.8％，现在被认为是在人类表现的惊人的范围内。这就提出了两个问题 - 人类的表现如何，我们还能驱动语音识别错误率？微软最近发表的一篇文章表明，我们已经取得了人类的成就。在试图验证这个陈述时，我们对两个对话任务进行了一套独立的人类表现测量，发现人类的表现可能比之前报道的要好得多，给社区带来了更难实现的目标。我们还报告了我们在这方面的努力，提出了一套声学和语言建模技术，将我们自己的英语对话电话LVCSR系统的字错误率降低到交换机/ CallHome子集的5.5％/ 10.3％至少在本文的写作中，Hub5 2000的评估是一个新的性能里程碑（虽然不是我们所称的人类表现！）。在声学方面，我们使用三种模型的分数融合：一个LSTM具有多个特征输入，第二个LSTM训练有说话者对抗性多任务学习和第三残差网（ResNet），具有25个卷积层和时间扩大的卷积。在语言建模方面，我们使用了字和字符LSTMs和卷积WaveNet风格的语言模型。

##### URL
[https://arxiv.org/abs/1703.02136](https://arxiv.org/abs/1703.02136)

##### PDF
[https://arxiv.org/pdf/1703.02136](https://arxiv.org/pdf/1703.02136)

