---
layout: post
title: "A non-projective greedy dependency parser with bidirectional LSTMs"
date: 2017-07-11 11:44:31
categories: arXiv_CL
tags: arXiv_CL Segmentation RNN
author: David Vilares, Carlos Gómez-Rodríguez
mathjax: true
---

* content
{:toc}

##### Abstract
The LyS-FASTPARSE team presents BIST-COVINGTON, a neural implementation of the Covington (2001) algorithm for non-projective dependency parsing. The bidirectional LSTM approach by Kipperwasser and Goldberg (2016) is used to train a greedy parser with a dynamic oracle to mitigate error propagation. The model participated in the CoNLL 2017 UD Shared Task. In spite of not using any ensemble methods and using the baseline segmentation and PoS tagging, the parser obtained good results on both macro-average LAS and UAS in the big treebanks category (55 languages), ranking 7th out of 33 teams. In the all treebanks category (LAS and UAS) we ranked 16th and 12th. The gap between the all and big categories is mainly due to the poor performance on four parallel PUD treebanks, suggesting that some `suffixed' treebanks (e.g. Spanish-AnCora) perform poorly on cross-treebank settings, which does not occur with the corresponding `unsuffixed' treebank (e.g. Spanish). By changing that, we obtain the 11th best LAS among all runs (official and unofficial). The code is made available at this https URL

##### Abstract (translated by Google)
LyS-FASTPARSE团队提出了BIST-COVINGTON，Covington（2001）算法的非投影依赖性解析的神经实现。 Kipperwasser和Goldberg（2016）的双向LSTM方法用于训练一个具有动态oracle的贪婪分析器，以减轻错误传播。该模型参加了CoNLL 2017 UD共享任务。尽管没有使用任何集成方法，并且使用基线分割和PoS标记，但是解析器在大型树库类别（55种语言）中的宏观平均LAS和UAS上获得了良好的结果，在33个小组中排名第七。在所有的树类（LAS和UAS）中，我们排名第16和第12。全部和大类之间的差距主要是由于在四个平行的PUD树库上表现不佳，这表明一些“后缀”树库（例如，西班牙 - 安科拉）在交叉树库设置上表现不佳，这与相应的“未固定的“树库（例如西班牙文）。通过改变这一点，我们获得了所有运行（官方和非官方）中排名第十一的LAS。该代码在此https URL中可用

##### URL
[https://arxiv.org/abs/1707.03228](https://arxiv.org/abs/1707.03228)

##### PDF
[https://arxiv.org/pdf/1707.03228](https://arxiv.org/pdf/1707.03228)

