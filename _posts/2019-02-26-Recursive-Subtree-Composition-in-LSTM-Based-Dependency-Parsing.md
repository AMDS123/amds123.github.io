---
layout: post
title: "Recursive Subtree Composition in LSTM-Based Dependency Parsing"
date: 2019-02-26 07:57:22
categories: arXiv_CL
tags: arXiv_CL RNN
author: Miryam de Lhoneux, Miguel Ballesteros, Joakim Nivre
mathjax: true
---

* content
{:toc}

##### Abstract
The need for tree structure modelling on top of sequence modelling is an open issue in neural dependency parsing. We investigate the impact of adding a tree layer on top of a sequential model by recursively composing subtree representations (composition) in a transition-based parser that uses features extracted by a BiLSTM. Composition seems superfluous with such a model, suggesting that BiLSTMs capture information about subtrees. We perform model ablations to tease out the conditions under which composition helps. When ablating the backward LSTM, performance drops and composition does not recover much of the gap. When ablating the forward LSTM, performance drops less dramatically and composition recovers a substantial part of the gap, indicating that a forward LSTM and composition capture similar information. We take the backward LSTM to be related to lookahead features and the forward LSTM to the rich history-based features both crucial for transition-based parsers. To capture history-based information, composition is better than a forward LSTM on its own, but it is even better to have a forward LSTM as part of a BiLSTM. We correlate results with language properties, showing that the improved lookahead of a backward LSTM is especially important for head-final languages.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.09781](http://arxiv.org/abs/1902.09781)

##### PDF
[http://arxiv.org/pdf/1902.09781](http://arxiv.org/pdf/1902.09781)

