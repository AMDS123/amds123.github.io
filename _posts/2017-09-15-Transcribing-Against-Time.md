---
layout: post
title: "Transcribing Against Time"
date: 2017-09-15 14:19:29
categories: arXiv_CL
tags: arXiv_CL
author: Matthias Sperber, Graham Neubig, Jan Niehues, Satoshi Nakamura, Alex Waibel
mathjax: true
---

* content
{:toc}

##### Abstract
We investigate the problem of manually correcting errors from an automatic speech transcript in a cost-sensitive fashion. This is done by specifying a fixed time budget, and then automatically choosing location and size of segments for correction such that the number of corrected errors is maximized. The core components, as suggested by previous research [1], are a utility model that estimates the number of errors in a particular segment, and a cost model that estimates annotation effort for the segment. In this work we propose a dynamic updating framework that allows for the training of cost models during the ongoing transcription process. This removes the need for transcriber enrollment prior to the actual transcription, and improves correction efficiency by allowing highly transcriber-adaptive cost modeling. We first confirm and analyze the improvements afforded by this method in a simulated study. We then conduct a realistic user study, observing efficiency improvements of 15% relative on average, and 42% for the participants who deviated most strongly from our initial, transcriber-agnostic cost model. Moreover, we find that our updating framework can capture dynamically changing factors, such as transcriber fatigue and topic familiarity, which we observe to have a large influence on the transcriber's working behavior.

##### Abstract (translated by Google)
我们以成本敏感的方式调查从自动语音记录中手动纠正错误的问题。这是通过指定一个固定的时间预算，然后自动选择段的位置和大小进行纠正，使纠正错误的数量最大化。正如以前的研究[1]所建议的，核心组件是一个实用模型，用于估计特定分段中错误的数量，以及一个估算分段注释工作量的成本模型。在这项工作中，我们提出了一个动态更新框架，允许在正在进行的转录过程中对成本模型进行培训。这使得在实际转录之前不需要抄录员注册，并且通过允许高度抄写适应的成本建模来提高校正效率。我们首先在模拟研究中确认和分析这种方法所提供的改进。然后，我们进行了一个现实的用户研究，观察效率提高了15％，平均相对提高了15％，而那些参与者的偏好程度最高，为42％。此外，我们发现，我们的更新框架可以捕捉动态变化的因素，如抄写员疲劳和主题熟悉，我们观察到对抄写员的工作行为有很大的影响。

##### URL
[https://arxiv.org/abs/1709.05227](https://arxiv.org/abs/1709.05227)

##### PDF
[https://arxiv.org/pdf/1709.05227](https://arxiv.org/pdf/1709.05227)

