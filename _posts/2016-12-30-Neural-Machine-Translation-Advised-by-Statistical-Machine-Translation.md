---
layout: post
title: 'Neural Machine Translation Advised by Statistical Machine Translation'
date: 2016-12-30 02:38:35
categories: arXiv_CL
tags: arXiv_CL NMT
author: Xing Wang, Zhengdong Lu, Zhaopeng Tu, Hang Li, Deyi Xiong, Min Zhang
---

* content
{:toc}

##### Abstract
Neural Machine Translation (NMT) is a new approach to machine translation that has made great progress in recent years. However, recent studies show that NMT generally produces fluent but inadequate translations (Tu et al. 2016b; Tu et al. 2016a; He et al. 2016; Tu et al. 2017). This is in contrast to conventional Statistical Machine Translation (SMT), which usually yields adequate but non-fluent translations. It is natural, therefore, to leverage the advantages of both models for better translations, and in this work we propose to incorporate SMT model into NMT framework. More specifically, at each decoding step, SMT offers additional recommendations of generated words based on the decoding information from NMT (e.g., the generated partial translation and attention history). Then we employ an auxiliary classifier to score the SMT recommendations and a gating function to combine the SMT recommendations with NMT generations, both of which are jointly trained within the NMT architecture in an end-to-end manner. Experimental results on Chinese-English translation show that the proposed approach achieves significant and consistent improvements over state-of-the-art NMT and SMT systems on multiple NIST test sets.

##### Abstract (translated by Google)
神经机器翻译（NMT）是近年来取得重大进展的机器翻译新方法。然而，最近的研究表明NMT通常产生流畅但不充分的翻译（Tu等2016b; Tu等2016a; He等2016; Tu等2017）。这与传统的统计机器翻译（SMT）相反，后者通常会产生足够的但不流利的翻译。因此，利用两种模式的优势来更好地翻译是很自然的，在这项工作中，我们建议将SMT模型纳入NMT框架。更具体地，在每个解码步骤中，SMT基于来自NMT的解码信息（例如，所生成的部分翻译和关注历史）提供所生成的词的附加推荐。然后，我们使用辅助分类器来评分SMT建议和门控功能，以将SMT建议与NMT代相结合，两者都是以NMT体系结构以端到端的方式联合培训的。汉英翻译的实验结果表明，所提出的方法在多个NIST测试集上实现了对最先进的NMT和SMT系统的显着和一致的改进。

##### URL
[https://arxiv.org/abs/1610.05150](https://arxiv.org/abs/1610.05150)

