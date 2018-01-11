---
layout: post
title: "Translating Pro-Drop Languages with Reconstruction Models"
date: 2018-01-10 07:53:22
categories: arXiv_CL
tags: arXiv_CL Attention NMT
author: Longyue Wang, Zhaopeng Tu, Shuming Shi, Tong Zhang, Yvette Graham, Qun Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Pronouns are frequently omitted in pro-drop languages, such as Chinese, generally leading to significant challenges with respect to the production of complete translations. To date, very little attention has been paid to the dropped pronoun (DP) problem within neural machine translation (NMT). In this work, we propose a novel reconstruction-based approach to alleviating DP translation problems for NMT models. Firstly, DPs within all source sentences are automatically annotated with parallel information extracted from the bilingual training corpus. Next, the annotated source sentence is reconstructed from hidden representations in the NMT model. With auxiliary training objectives, in terms of reconstruction scores, the parameters associated with the NMT model are guided to produce enhanced hidden representations that are encouraged as much as possible to embed annotated DP information. Experimental results on both Chinese-English and Japanese-English dialogue translation tasks show that the proposed approach significantly and consistently improves translation performance over a strong NMT baseline, which is directly built on the training data annotated with DPs.

##### Abstract (translated by Google)
在像中文这样的促销语言中，代词经常被忽略，通常在完成翻译的过程中产生重大的挑战。迄今为止，关于神经机器翻译（NMT）中的下降代词（DP）问题的关注很少。在这项工作中，我们提出了一种新的基于重建的方法来减轻NMT模型的DP翻译问题。首先，在双语训练语料库中提取的并行信息自动标注所有源句子中的DP。接下来，注释的源语句在NMT模型中由隐藏表示重构。通过辅助训练目标，就重构得分而言，引导与NMT模型相关的参数以产生增强的隐藏表示，其被尽可能地鼓励以嵌入注释的DP信息。汉英对话翻译任务的实验结果表明，所提出的方法在强大的NMT基线上显着且一致地提高翻译性能，该基线直接建立在用DP注释的训练数据上。

##### URL
[https://arxiv.org/abs/1801.03257](https://arxiv.org/abs/1801.03257)

##### PDF
[https://arxiv.org/pdf/1801.03257](https://arxiv.org/pdf/1801.03257)

