---
layout: post
title: "Bridging the Gap between Training and Inference for Neural Machine Translation"
date: 2019-06-06 07:15:52
categories: arXiv_CL
tags: arXiv_CL NMT Inference
author: Wen Zhang, Yang Feng, Fandong Meng, Di You, Qun Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Neural Machine Translation (NMT) generates target words sequentially in the way of predicting the next word conditioned on the context words. At training time, it predicts with the ground truth words as context while at inference it has to generate the entire sequence from scratch. This discrepancy of the fed context leads to error accumulation among the way. Furthermore, word-level training requires strict matching between the generated sequence and the ground truth sequence which leads to overcorrection over different but reasonable translations. In this paper, we address these issues by sampling context words not only from the ground truth sequence but also from the predicted sequence by the model during training, where the predicted sequence is selected with a sentence-level optimum. Experiment results on Chinese-&gt;English and WMT'14 English-&gt;German translation tasks demonstrate that our approach can achieve significant improvements on multiple datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.02448](http://arxiv.org/abs/1906.02448)

##### PDF
[http://arxiv.org/pdf/1906.02448](http://arxiv.org/pdf/1906.02448)

