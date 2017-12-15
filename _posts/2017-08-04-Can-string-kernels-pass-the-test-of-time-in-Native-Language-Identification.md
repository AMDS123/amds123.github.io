---
layout: post
title: "Can string kernels pass the test of time in Native Language Identification?"
date: 2017-08-04 14:52:49
categories: arXiv_CL
tags: arXiv_CL GAN
author: Radu Tudor Ionescu, Marius Popescu
mathjax: true
---

* content
{:toc}

##### Abstract
We describe a machine learning approach for the 2017 shared task on Native Language Identification (NLI). The proposed approach combines several kernels using multiple kernel learning. While most of our kernels are based on character p-grams (also known as n-grams) extracted from essays or speech transcripts, we also use a kernel based on i-vectors, a low-dimensional representation of audio recordings, provided by the shared task organizers. For the learning stage, we choose Kernel Discriminant Analysis (KDA) over Kernel Ridge Regression (KRR), because the former classifier obtains better results than the latter one on the development set. In our previous work, we have used a similar machine learning approach to achieve state-of-the-art NLI results. The goal of this paper is to demonstrate that our shallow and simple approach based on string kernels (with minor improvements) can pass the test of time and reach state-of-the-art performance in the 2017 NLI shared task, despite the recent advances in natural language processing. We participated in all three tracks, in which the competitors were allowed to use only the essays (essay track), only the speech transcripts (speech track), or both (fusion track). Using only the data provided by the organizers for training our models, we have reached a macro F1 score of 86.95% in the closed essay track, a macro F1 score of 87.55% in the closed speech track, and a macro F1 score of 93.19% in the closed fusion track. With these scores, our team (UnibucKernel) ranked in the first group of teams in all three tracks, while attaining the best scores in the speech and the fusion tracks.

##### Abstract (translated by Google)
我们描述了2017年的母语识别（NLI）共享任务的机器学习方法。所提出的方法结合了多个内核使用多核学习。虽然我们的大多数内核基于从散文或语音转录本中提取的字符p-gram（也称为n-gram），但我们也使用基于i-矢量的内核，这是音频记录的低维表示，由共享任务组织者。在学习阶段，我们选择核岭分析（KRR）的核判别分析（KDA），因为前者的分类器在开发集合上获得比后者更好的结果。在我们以前的工作中，我们使用了类似的机器学习方法来实现最先进的NLI结果。本文的目的是要证明，尽管最近取得了一些进展，但是基于字符串内核的简单而简单的方法（稍有改进）可以在2017 NLI共享任务中通过时间测试并达到最新的性能在自然语言处理。我们参加了所有的三个轨道，其中竞争对手被允许使用只有散文（散文轨道），只有语音记录（语音轨道），或两者（融合轨道）。我们只使用主办方提供的数据进行训练，在封闭式论文中宏观F1分为86.95％，封闭式言语轨迹中宏观F1分为87.55％，宏观F1分为93.19％在封闭的融合轨道。凭借这些成绩，我们的团队（UnibucKernel）在三条曲目中排在第一组，同时在演讲和融合曲目中获得最高分数。

##### URL
[https://arxiv.org/abs/1707.08349](https://arxiv.org/abs/1707.08349)

##### PDF
[https://arxiv.org/pdf/1707.08349](https://arxiv.org/pdf/1707.08349)

