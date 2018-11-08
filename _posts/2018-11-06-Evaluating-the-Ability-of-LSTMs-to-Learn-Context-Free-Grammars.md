---
layout: post
title: "Evaluating the Ability of LSTMs to Learn Context-Free Grammars"
date: 2018-11-06 20:07:47
categories: arXiv_CL
tags: arXiv_CL RNN Prediction
author: Luzi Sennhauser, Robert C. Berwick
mathjax: true
---

* content
{:toc}

##### Abstract
While long short-term memory (LSTM) neural net architectures are designed to capture sequence information, human language is generally composed of hierarchical structures. This raises the question as to whether LSTMs can learn hierarchical structures. We explore this question with a well-formed bracket prediction task using two types of brackets modeled by an LSTM. Demonstrating that such a system is learnable by an LSTM is the first step in demonstrating that the entire class of CFLs is also learnable. We observe that the model requires exponential memory in terms of the number of characters and embedded depth, where a sub-linear memory should suffice. Still, the model does more than memorize the training input. It learns how to distinguish between relevant and irrelevant information. On the other hand, we also observe that the model does not generalize well. We conclude that LSTMs do not learn the relevant underlying context-free rules, suggesting the good overall performance is attained rather by an efficient way of evaluating nuisance variables. LSTMs are a way to quickly reach good results for many natural language tasks, but to understand and generate natural language one has to investigate other concepts that can make more direct use of natural language's structural nature.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.02611](http://arxiv.org/abs/1811.02611)

##### PDF
[http://arxiv.org/pdf/1811.02611](http://arxiv.org/pdf/1811.02611)

