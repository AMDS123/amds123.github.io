---
layout: post
title: "Going Deeper for Multilingual Visual Sentiment Detection"
date: 2016-05-30 12:57:44
categories: arXiv_CL
tags: arXiv_CL Sentiment Object_Detection Ontology Detection
author: Brendan Jou, Shih-Fu Chang
mathjax: true
---

* content
{:toc}

##### Abstract
This technical report details several improvements to the visual concept detector banks built on images from the Multilingual Visual Sentiment Ontology (MVSO). The detector banks are trained to detect a total of 9,918 sentiment-biased visual concepts from six major languages: English, Spanish, Italian, French, German and Chinese. In the original MVSO release, adjective-noun pair (ANP) detectors were trained for the six languages using an AlexNet-styled architecture by fine-tuning from DeepSentiBank. Here, through a more extensive set of experiments, parameter tuning, and training runs, we detail and release higher accuracy models for detecting ANPs across six languages from the same image pool and setting as in the original release using a more modern architecture, GoogLeNet, providing comparable or better performance with reduced network parameter cost. In addition, since the image pool in MVSO can be corrupted by user noise from social interactions, we partitioned out a sub-corpus of MVSO images based on tag-restricted queries for higher fidelity labels. We show that as a result of these higher fidelity labels, higher performing AlexNet-styled ANP detectors can be trained using the tag-restricted image subset as compared to the models in full corpus. We release all these newly trained models for public research use along with the list of tag-restricted images from the MVSO dataset.

##### Abstract (translated by Google)
本技术报告详细介绍了基于多语言视觉情感本体（MVSO）图像的视觉概念检测器库的一些改进。探测器银行经过培训，共检测出六种主要语言（英语，西班牙语，意大利语，法语，德语和中文）的9,918个情感偏差视觉概念。在最初的MVSO版本中，形容词 - 名词对（ANP）检测器通过从DeepSentiBank进行微调，使用AlexNet风格的体系结构对六种语言进行了培训。在这里，通过更广泛的一系列实验，参数调整和训练运行，我们详细地发布了更高精度的模型，用于从同一个图像池中检测六种语言的ANP，并使用更现代的架构GoogLeNet，通过降低网络参数成本提供可比的或更好的性能。另外，由于MVSO中的图像池可能受到来自社交交互的用户噪声的影响，因此我们基于标签限制查询为高保真度标签划分出MVSO​​图像的子集。我们表明，由于这些更高保真标签，更高性能的AlexNet风格的ANP检测器可以使用标签限制图像子集与全部语料库中的模型进行比较。我们发布了所有这些新公开的研究模型，以及来自MVSO数据集的标签限制图片列表。

##### URL
[https://arxiv.org/abs/1605.09211](https://arxiv.org/abs/1605.09211)

##### PDF
[https://arxiv.org/pdf/1605.09211](https://arxiv.org/pdf/1605.09211)

