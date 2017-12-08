---
layout: post
title: "Hungarian Layer: Logics Empowered Neural Architecture"
date: 2017-12-07 10:02:56
categories: arXiv_CL
tags: arXiv_CL RNN
author: Han Xiao, Lian Meng
mathjax: true
---

* content
{:toc}

##### Abstract
Neural architecture is a purely numeric framework, which fits the data as a continuous function. However, lacking of logic flow (e.g. \textit{if, for, while}), traditional algorithms (e.g. \textit{Hungarian algorithm, A$^*$ searching, decision tress algorithm}) could not be embedded into this paradigm, which limits the theories and applications. In this paper, we reform the calculus graph as a dynamic process, which is guided by logic flow. Within our novel methodology, traditional algorithms could empower numerical neural network. Specifically, regarding the subject of sentence matching, we reformulate this issue as the form of task-assignment, which is solved by Hungarian algorithm. First, our model applies BiLSTM to parse the sentences. Then Hungarian layer aligns the matching positions. Last, we transform the matching results for soft-max regression by another BiLSTM. Extensive experiments show that our model outperforms other state-of-the-art baselines substantially.

##### Abstract (translated by Google)
神经结构是一个纯粹的数字框架，它将数据作为一个连续函数来拟合。然而，传统的算法（例如\ textit {匈牙利算法，A $ ^ * $搜索，决策树算法}）缺乏逻辑流程（例如\ textit {if，for，while}）不能嵌入到这个范例中，限制了理论和应用。在本文中，我们将微积分图作为一个动态过程进行改造，并以逻辑流程为指导。在我们的新方法中，传统的算法可以赋予数值神经网络。具体而言，关于句子匹配的主题，我们将这个问题作为任务分配的形式进行了重新表述，这是匈牙利算法解决的。首先，我们的模型应用BiLSTM来解析句子。然后匈牙利层对齐匹配的位置。最后，我们通过另一个BiLSTM来转换soft-max回归的匹配结果。大量实验表明，我们的模型大大超过了其他最先进的基线。

##### URL
[http://arxiv.org/abs/1712.02555](http://arxiv.org/abs/1712.02555)

##### PDF
[http://arxiv.org/pdf/1712.02555](http://arxiv.org/pdf/1712.02555)

