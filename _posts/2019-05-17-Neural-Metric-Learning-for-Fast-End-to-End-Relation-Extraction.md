---
layout: post
title: "Neural Metric Learning for Fast End-to-End Relation Extraction"
date: 2019-05-17 20:20:22
categories: arXiv_CL
tags: arXiv_CL Relation_Extraction Optimization Relation Recognition
author: Tung Tran, Ramakanth Kavuluru
mathjax: true
---

* content
{:toc}

##### Abstract
Relation extraction (RE) is an indispensable information extraction task in several disciplines. RE models typically assume that named entity recognition (NER) is already performed in a previous step by another independent model. Several recent efforts, under the theme of end-to-end RE, seek to exploit inter-task correlations by modeling both NER and RE tasks jointly. Earlier work in this area commonly reduces the task to a table-filling problem wherein an additional expensive decoding step involving beam search is applied to obtain globally consistent cell labels. In efforts that do not employ table-filling, global optimization in the form of CRFs with Viterbi decoding for the NER component is still necessary for competitive performance. We introduce a novel neural architecture utilizing the table structure, based on repeated applications of 2D convolutions for pooling local dependency and metric-based features, without the need for global optimization. We validate our model on the ADE and CoNLL04 datasets for end-to-end RE and demonstrate $\approx 1\%$ gain (in F-score) over prior best results with training and testing times that are nearly four times faster --- the latter highly advantageous for time-sensitive end user applications.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.07458](http://arxiv.org/abs/1905.07458)

##### PDF
[http://arxiv.org/pdf/1905.07458](http://arxiv.org/pdf/1905.07458)

