---
layout: post
title: "How Large a Vocabulary Does Text Classification Need? A Variational Approach to Vocabulary Selection"
date: 2019-02-27 05:57:13
categories: arXiv_CL
tags: arXiv_CL Text_Classification Classification Deep_Learning
author: Wenhu Chen, Yu Su, Yilin Shen, Zhiyu Chen, Xifeng Yan, William Wang
mathjax: true
---

* content
{:toc}

##### Abstract
With the rapid development in deep learning, deep neural networks have been widely adopted in many real-life natural language applications. Under deep neural networks, a pre-defined vocabulary is required to vectorize text inputs. The canonical approach to select pre-defined vocabulary is based on the word frequency, where a threshold is selected to cut off the long tail distribution. However, we observed that such simple approach could easily lead to under-sized vocabulary or over-sized vocabulary issues. Therefore, we are interested in understanding how the end-task classification accuracy is related to the vocabulary size and what is the minimum required vocabulary size to achieve a specific performance. In this paper, we provide a more sophisticated variational vocabulary dropout (VVD) based on variational dropout to perform vocabulary selection, which can intelligently select the subset of the vocabulary to achieve the required performance. To evaluate different algorithms on the newly proposed vocabulary selection problem, we propose two new metrics: Area Under Accuracy-Vocab Curve and Vocab Size under X\% Accuracy Drop. Through extensive experiments on various NLP classification tasks, our variational framework is shown to significantly outperform the frequency-based and other selection baselines on these metrics.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.10339](http://arxiv.org/abs/1902.10339)

##### PDF
[http://arxiv.org/pdf/1902.10339](http://arxiv.org/pdf/1902.10339)

