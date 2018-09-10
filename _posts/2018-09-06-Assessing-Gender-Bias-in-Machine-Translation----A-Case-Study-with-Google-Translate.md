---
layout: post
title: "Assessing Gender Bias in Machine Translation -- A Case Study with Google Translate"
date: 2018-09-06 20:39:23
categories: arXiv_CL
tags: arXiv_CL
author: Marcelo O. R. Prates, Pedro H. C. Avelar, Luis Lamb
mathjax: true
---

* content
{:toc}

##### Abstract
Recently there has been a growing concern about machine bias, where trained statistical models grow to reflect controversial societal asymmetries, such as gender or racial bias. A significant number of AI tools have recently been suggested to be harmfully biased towards some minority, with reports of racist criminal behavior predictors, Iphone X failing to differentiate between two Asian people and Google photos' mistakenly classifying black people as gorillas. Although a systematic study of such biases can be difficult, we believe that automated translation tools can be exploited through gender neutral languages to yield a window into the phenomenon of gender bias in AI. In this paper, we start with a comprehensive list of job positions from the U.S. Bureau of Labor Statistics (BLS) and used it to build sentences in constructions like "He/She is an Engineer" in 12 different gender neutral languages such as Hungarian, Chinese, Yoruba, and several others. We translate these sentences into English using the Google Translate API, and collect statistics about the frequency of female, male and gender-neutral pronouns in the translated output. We show that GT exhibits a strong tendency towards male defaults, in particular for fields linked to unbalanced gender distribution such as STEM jobs. We ran these statistics against BLS' data for the frequency of female participation in each job position, showing that GT fails to reproduce a real-world distribution of female workers. We provide experimental evidence that even if one does not expect in principle a 50:50 pronominal gender distribution, GT yields male defaults much more frequently than what would be expected from demographic data alone. We are hopeful that this work will ignite a debate about the need to augment current statistical translation tools with debiasing techniques which can already be found in the scientific literature.

##### Abstract (translated by Google)
最近人们越来越关注机器偏差，经过训练的统计模型可以反映出有争议的社会不对称，例如性别或种族偏见。最近有人提出大量人工智能工具对某些少数人有害，有报道称种族主义犯罪行为预测因素，Iphone X未能区分两个亚洲人和谷歌照片“错误地将黑人分类为大猩猩”。尽管对这种偏见进行系统研究可能很困难，但我们认为可以通过性别中性语言利用自动翻译工具，从而为人工智能中的性别偏见现象提供一个窗口。在本文中，我们从美国劳工统计局（BLS）的工作岗位列表开始，并用它来构建句子，如“他/她是工程师”等12种不同性别中性语言，如匈牙利语，中国人，约鲁巴人和其他几个人。我们使用谷歌翻译API将这些句子翻译成英语，并收集有关翻译输出中女性，男性和性别中性代词的频率的统计数据。我们表明，GT表现出强烈的男性违约倾向，特别是与STEM工作等不平衡性别分布相关的领域。我们根据BLS的数据对这些统计数据进行了统计，了解女性参与每个职位的频率，表明GT无法重现女性工作者的真实分布。我们提供的实验证据表明，即使人们原则上没有预期50:50的代名词性别分布，GT也会比单独的人口统计数据更频繁地产生男性违约。我们希望这项工作将引发关于需要利用已经在科学文献中找到的去除技术来增强现有统计翻译工具的辩论。

##### URL
[https://arxiv.org/abs/1809.02208](https://arxiv.org/abs/1809.02208)

##### PDF
[https://arxiv.org/pdf/1809.02208](https://arxiv.org/pdf/1809.02208)

