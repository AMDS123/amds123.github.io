---
layout: post
title: 'Resolving Language and Vision Ambiguities Together: Joint Segmentation & Prepositional Attachment Resolution in Captioned Scenes'
date: 2017-12-06 08:49:46
categories: arXiv_CV
tags: arXiv_CV Segmentation Caption Semantic_Segmentation
author: Gordon Christie, Ankit Laddha, Aishwarya Agrawal, Stanislaw Antol, Yash Goyal, Kevin Kochersberger, Dhruv Batra
---

* content
{:toc}

##### Abstract
We present an approach to simultaneously perform semantic segmentation and prepositional phrase attachment resolution for captioned images. Some ambiguities in language cannot be resolved without simultaneously reasoning about an associated image. If we consider the sentence "I shot an elephant in my pajamas", looking at language alone (and not using common sense), it is unclear if it is the person or the elephant wearing the pajamas or both. Our approach produces a diverse set of plausible hypotheses for both semantic segmentation and prepositional phrase attachment resolution that are then jointly reranked to select the most consistent pair. We show that our semantic segmentation and prepositional phrase attachment resolution modules have complementary strengths, and that joint reasoning produces more accurate results than any module operating in isolation. Multiple hypotheses are also shown to be crucial to improved multiple-module reasoning. Our vision and language approach significantly outperforms the Stanford Parser (De Marneffe et al., 2006) by 17.91% (28.69% relative) and 12.83% (25.28% relative) in two different experiments. We also make small improvements over DeepLab-CRF (Chen et al., 2015).

##### Abstract (translated by Google)
我们提出了一种同时为字幕图像执行语义分割和介词短语附件分辨率的方法。如果不同时推理相关的图像，语言中的一些歧义就不能被解决。如果我们考虑“我穿着睡衣拍大象”这个句子，单单看语言（而不是用常识），还不清楚是穿着睡衣的人还是穿着睡衣的大象。我们的方法为语义分段和介词短语附件分辨率产生了一系列合理的假设，然后将这些假设联合重新排列以选择最一致的对。我们表明，我们的语义分割和介词短语附件解析模块具有互补的优势，并且联合推理产生比任何独立操作的模块更准确的结果。多重假设对于改善多模块推理也是至关重要的。我们的视觉和语言方法在两个不同的实验中显着优于斯坦福分析器（De Marneffe等，2006）17.91％（28.69％相对）和12.83％（相对25.28％）。我们也对DeepLab-CRF做了小的改进（Chen et al。，2015）。

##### URL
[https://arxiv.org/abs/1604.02125](https://arxiv.org/abs/1604.02125)

