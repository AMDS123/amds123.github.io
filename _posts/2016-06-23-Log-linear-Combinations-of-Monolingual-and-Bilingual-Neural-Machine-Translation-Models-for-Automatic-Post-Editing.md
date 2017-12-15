---
layout: post
title: "Log-linear Combinations of Monolingual and Bilingual Neural Machine Translation Models for Automatic Post-Editing"
date: 2016-06-23 13:15:50
categories: arXiv_CL
tags: arXiv_CL
author: Marcin Junczys-Dowmunt, Roman Grundkiewicz
mathjax: true
---

* content
{:toc}

##### Abstract
This paper describes the submission of the AMU (Adam Mickiewicz University) team to the Automatic Post-Editing (APE) task of WMT 2016. We explore the application of neural translation models to the APE problem and achieve good results by treating different models as components in a log-linear model, allowing for multiple inputs (the MT-output and the source) that are decoded to the same target language (post-edited translations). A simple string-matching penalty integrated within the log-linear model is used to control for higher faithfulness with regard to the raw machine translation output. To overcome the problem of too little training data, we generate large amounts of artificial data. Our submission improves over the uncorrected baseline on the unseen test set by -3.2\% TER and +5.5\% BLEU and outperforms any other system submitted to the shared-task by a large margin.

##### Abstract (translated by Google)
本文介绍了AMU（亚当密茨凯维奇大学）团队提交给WMT 2016的自动编辑后（APE）任务。我们探讨了神经翻译模型在APE问题中的应用，并将不同模型作为组件在对数线性模型中，允许解码为相同目标语言的多个输入（MT输出和源）（编辑后的翻译）。对数线性模型中集成的简单字符串匹配惩罚被用来控制关于原始机器翻译输出的更高忠诚度。为了克服训练数据太少的问题，我们生成大量的人造数据。我们的提交将未经验证的测试集的未修正基线提高了-3.2％TER和+5.5％BLEU，并且大大超过了任何其他提交给共享任务的系统。

##### URL
[https://arxiv.org/abs/1605.04800](https://arxiv.org/abs/1605.04800)

##### PDF
[https://arxiv.org/pdf/1605.04800](https://arxiv.org/pdf/1605.04800)

