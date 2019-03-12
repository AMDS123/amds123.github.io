---
layout: post
title: "HLT@SUDA at SemEval 2019 Task 1: UCCA Graph Parsing as Constituent Tree Parsing"
date: 2019-03-11 07:46:03
categories: arXiv_CL
tags: arXiv_CL Embedding Classification
author: Wei Jiang, Yu Zhang, Zhenghua Li, Min Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
This paper describes a simple UCCA semantic graph parsing approach. The key idea is to convert a UCCA semantic graph into a constituent tree, in which extra labels are deliberately designed to mark remote and discontinuous links for future recovery. In this way, we can make use of existing syntactic parsing techniques. Based on the data statistics, we recover discontinuous links directly according to the output labels of the constituent parser and use a biaffine classification model to recover the more complex remote links. The classification model and the constituent parser are simultaneously trained under the multi-task learning framework. We use the multilingual BERT as extra features in the open tracks. Our system ranks the first place in the six English/German closed/open tracks among seven participating systems. For the seventh cross-lingual track, where there is little training data for French, we propose a language embedding approach to utilize English and German training data, and our result ranks the second place.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1903.04153](https://arxiv.org/abs/1903.04153)

##### PDF
[https://arxiv.org/pdf/1903.04153](https://arxiv.org/pdf/1903.04153)

