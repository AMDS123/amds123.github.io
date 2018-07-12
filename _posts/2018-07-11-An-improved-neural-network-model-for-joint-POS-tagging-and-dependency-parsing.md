---
layout: post
title: "An improved neural network model for joint POS tagging and dependency parsing"
date: 2018-07-11 05:47:33
categories: arXiv_CL
tags: arXiv_CL RNN
author: Dat Quoc Nguyen, Karin Verspoor
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel neural network model for joint part-of-speech (POS) tagging and dependency parsing. Our model extends the well-known BIST graph-based dependency parser (Kiperwasser and Goldberg, 2016) by incorporating a BiLSTM-based tagging component to produce automatically predicted POS tags for the parser. On the benchmark English Penn treebank, our model obtains strong UAS and LAS scores at 94.51% and 92.87%, respectively, producing 1.5+% absolute improvements to the BIST graph-based parser, and also obtaining a state-of-the-art POS tagging accuracy at 97.97%. In addition, experimental results on parsing 61 big Universal Dependencies treebanks from raw texts show that our model outperforms the baseline UDPipe (Straka and Strakova, 2017) with 0.8% higher average POS tagging score and 3.6% higher average LAS score. Our code and pre-trained models are available at: https://github.com/datquocnguyen/jPTDP

##### Abstract (translated by Google)
我们提出了一种新的神经网络模型，用于联合词性（POS）标记和依赖性解析。我们的模型通过结合基于BiLSTM的标记组件来扩展着名的基于BIST图形的依赖性解析器（Kiperwasser和Goldberg，2016），以便为解析器生成自动预测的POS标记。在基准英语Penn树库上，我们的模型获得了强大的UAS和LAS分数分别为94.51％和92.87％，对基于BIST图的解析器产生了1.5 +％的绝对改进，并且还获得了最先进的POS标记准确率为97.97％。此外，从原始文本解析61大Universal Dependencies树库的实验结果表明，我们的模型优于基线UDPipe（Straka和Strakova，2017），平均POS标记得分高0.8％，平均LAS得分高3.6％。我们的代码和预先训练的模型可在以下网址获得：https：//github.com/datquocnguyen/jPTDP

##### URL
[http://arxiv.org/abs/1807.03955](http://arxiv.org/abs/1807.03955)

##### PDF
[http://arxiv.org/pdf/1807.03955](http://arxiv.org/pdf/1807.03955)

