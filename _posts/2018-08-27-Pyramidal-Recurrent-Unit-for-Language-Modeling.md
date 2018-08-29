---
layout: post
title: "Pyramidal Recurrent Unit for Language Modeling"
date: 2018-08-27 20:31:27
categories: arXiv_CL
tags: arXiv_CL RNN Language_Model
author: Sachin Mehta, Rik Koncel-Kedziorski, Mohammad Rastegari, Hannaneh Hajishirzi
mathjax: true
---

* content
{:toc}

##### Abstract
LSTMs are powerful tools for modeling contextual information, as evidenced by their success at the task of language modeling. However, modeling contexts in very high dimensional space can lead to poor generalizability. We introduce the Pyramidal Recurrent Unit (PRU), which enables learning representations in high dimensional space with more generalization power and fewer parameters. PRUs replace the linear transformation in LSTMs with more sophisticated interactions including pyramidal and grouped linear transformations. This architecture gives strong results on word-level language modeling while reducing the number of parameters significantly. In particular, PRU improves the perplexity of a recent state-of-the-art language model Merity et al. (2018) by up to 1.3 points while learning 15-20% fewer parameters. For similar number of model parameters, PRU outperforms all previous RNN models that exploit different gating mechanisms and transformations. We provide a detailed examination of the PRU and its behavior on the language modeling tasks. Our code is open-source and available at https://sacmehta.github.io/PRU/

##### Abstract (translated by Google)
LSTM是用于建模上下文信息的强大工具，正如他们在语言建模任务中的成功所证明的那样。但是，在非常高维空间中建模上下文会导致可普遍性差。我们介绍了金字塔循环单元（PRU），它可以在高维空间中学习表示，具有更强的泛化能力和更少的参数。 PRU用LSTM中的线性变换替换更复杂的相互作用，包括金字塔形和分组线性变换。该架构在字级语言建模方面提供了强大的结果，同时显着减少了参数的数量。特别是，PRU改善了最近最先进的语言模型Merity等人的困惑。 （2018）高达1.3分，同时学习参数减少15-20％。对于相似数量的模型参数，PRU优于所有先前使用不同选通机制和变换的RNN模型。我们详细介绍了PRU及其在语言建模任务中的行为。我们的代码是开源的，可从https://sacmehta.github.io/PRU/获取

##### URL
[http://arxiv.org/abs/1808.09029](http://arxiv.org/abs/1808.09029)

##### PDF
[http://arxiv.org/pdf/1808.09029](http://arxiv.org/pdf/1808.09029)

