---
layout: post
title: "End-to-End Speech Translation with Knowledge Distillation"
date: 2019-04-17 04:00:52
categories: arXiv_CL
tags: arXiv_CL Knowledge Attention Speech_Recognition Recognition
author: Yuchen Liu, Hao Xiong, Zhongjun He, Jiajun Zhang, Hua Wu, Haifeng Wang, Chengqing Zong
mathjax: true
---

* content
{:toc}

##### Abstract
End-to-end speech translation (ST), which directly translates from source language speech into target language text, has attracted intensive attentions in recent years. Compared to conventional pipeline systems, end-to-end ST models have advantages of lower latency, smaller model size and less error propagation. However, the combination of speech recognition and text translation in one model is more difficult than each of these two tasks. In this paper, we propose a knowledge distillation approach to improve ST model by transferring the knowledge from text translation model. Specifically, we first train a text translation model, regarded as a teacher model, and then ST model is trained to learn output probabilities from teacher model through knowledge distillation. Experiments on English- French Augmented LibriSpeech and English-Chinese TED corpus show that end-to-end ST is possible to implement on both similar and dissimilar language pairs. In addition, with the instruction of teacher model, end-to-end ST model can gain significant improvements by over 3.5 BLEU points.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08075](http://arxiv.org/abs/1904.08075)

##### PDF
[http://arxiv.org/pdf/1904.08075](http://arxiv.org/pdf/1904.08075)

