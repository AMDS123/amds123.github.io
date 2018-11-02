---
layout: post
title: "Hierarchical Long Short-Term Concurrent Memory for Human Interaction Recognition"
date: 2018-11-01 07:36:28
categories: arXiv_CV
tags: arXiv_CV Action_Recognition RNN Recognition
author: Xiangbo Shu, Jinhui Tang, Guo-Jun Qi, Wei Liu, Jian Yang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we aim to address the problem of human interaction recognition in videos by exploring the long-term inter-related dynamics among multiple persons. Recently, Long Short-Term Memory (LSTM) has become a popular choice to model individual dynamic for single-person action recognition due to its ability of capturing the temporal motion information in a range. However, existing RNN models focus only on capturing the dynamics of human interaction by simply combining all dynamics of individuals or modeling them as a whole. Such models neglect the inter-related dynamics of how human interactions change over time. To this end, we propose a novel Hierarchical Long Short-Term Concurrent Memory (H-LSTCM) to model the long-term inter-related dynamics among a group of persons for recognizing the human interactions. Specifically, we first feed each person's static features into a Single-Person LSTM to learn the single-person dynamic. Subsequently, the outputs of all Single-Person LSTM units are fed into a novel Concurrent LSTM (Co-LSTM) unit, which mainly consists of multiple sub-memory units, a new cell gate and a new co-memory cell. In a Co-LSTM unit, each sub-memory unit stores individual motion information, while this Co-LSTM unit selectively integrates and stores inter-related motion information between multiple interacting persons from multiple sub-memory units via the cell gate and co-memory cell, respectively. Extensive experiments on four public datasets validate the effectiveness of the proposed H-LSTCM by comparing against baseline and state-of-the-art methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.00270](http://arxiv.org/abs/1811.00270)

##### PDF
[http://arxiv.org/pdf/1811.00270](http://arxiv.org/pdf/1811.00270)

