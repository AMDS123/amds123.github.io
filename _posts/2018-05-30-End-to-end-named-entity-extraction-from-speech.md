---
layout: post
title: "End-to-end named entity extraction from speech"
date: 2018-05-30 15:56:22
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Optimization Recognition
author: Sahar Ghannay, Antoine Caubri&#xe8;re, Yannick Est&#xe8;ve, Antoine Laurent, Emmanuel Morin
mathjax: true
---

* content
{:toc}

##### Abstract
Named entity recognition (NER) is among SLU tasks that usually extract semantic information from textual documents. Until now, NER from speech is made through a pipeline process that consists in processing first an automatic speech recognition (ASR) on the audio and then processing a NER on the ASR outputs. Such approach has some disadvantages (error propagation, metric to tune ASR systems sub-optimal in regards to the final task, reduced space search at the ASR output level...) and it is known that more integrated approaches outperform sequential ones, when they can be applied. In this paper, we present a first study of end-to-end approach that directly extracts named entities from speech, though a unique neural architecture. On a such way, a joint optimization is able for both ASR and NER. Experiments are carried on French data easily accessible, composed of data distributed in several evaluation campaign. Experimental results show that this end-to-end approach provides better results (F-measure=0.69 on test data) than a classical pipeline approach to detect named entity categories (F-measure=0.65).

##### Abstract (translated by Google)
命名实体识别（NER）是通常从文本文档中提取语义信息的SLU任务之一。到目前为止，语音中的NER是通过流水线处理完成的，首先处理音频上的自动语音识别（ASR），然后处理ASR输出上的NER。这种方法有一些缺点（错误传播，衡量ASR系统的最佳任务是次优的，在ASR输出水平上减少空间搜索...），并且众所周知，更多的集成方法胜过顺序的方法，可以应用。在本文中，我们介绍了一种直接从语音中提取命名实体的端到端方法的首次研究，尽管它是一种独特的神经结构。在这种情况下，ASR和NER都可以进行联合优化。对法国数据进行实验很容易，数据由几次评估活动分发。实验结果表明，与经典的检测命名实体类别的流水线方法（F-measure = 0.65）相比，这种端到端方法提供了更好的结果（测试数据上的F-measure = 0.69）。

##### URL
[http://arxiv.org/abs/1805.12045](http://arxiv.org/abs/1805.12045)

##### PDF
[http://arxiv.org/pdf/1805.12045](http://arxiv.org/pdf/1805.12045)

