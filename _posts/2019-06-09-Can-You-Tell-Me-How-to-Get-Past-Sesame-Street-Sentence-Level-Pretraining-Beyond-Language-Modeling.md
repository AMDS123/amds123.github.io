---
layout: post
title: "Can You Tell Me How to Get Past Sesame Street? Sentence-Level Pretraining Beyond Language Modeling"
date: 2019-06-09 18:00:27
categories: arXiv_CL
tags: arXiv_CL Transfer_Learning Language_Model
author: Samuel R. Bowman, Ellie Pavlick, Edouard Grave, Benjamin Van Durme, Alex Wang, Jan Hula, Patrick Xia, Raghavendra Pappagari, R. Thomas McCoy, Roma Patel, Najoung Kim, Ian Tenney, Yinghui Huang, Katherin Yu, Shuning Jin, Berlin Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Natural language understanding has recently seen a surge of progress with the use of sentence encoders like ELMo (Peters et al., 2018a) and BERT (Devlin et al., 2019) which are pretrained on variants of language modeling. We conduct the first large-scale systematic study of candidate pretraining tasks, comparing 19 different tasks both as alternatives and complements to language modeling. Our primary results support the use language modeling, especially when combined with pretraining on additional labeled-data tasks. However, our results are mixed across pretraining tasks and show some concerning trends: In ELMo's pretrain-then-freeze paradigm, random baselines are worryingly strong and results vary strikingly across target tasks. In addition, fine-tuning BERT on an intermediate task often negatively impacts downstream transfer. In a more positive trend, we see modest gains from multitask training, suggesting the development of more sophisticated multitask and transfer learning techniques as an avenue for further research.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.10860](http://arxiv.org/abs/1812.10860)

##### PDF
[http://arxiv.org/pdf/1812.10860](http://arxiv.org/pdf/1812.10860)

