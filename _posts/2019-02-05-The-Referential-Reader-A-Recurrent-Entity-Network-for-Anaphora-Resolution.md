---
layout: post
title: "The Referential Reader: A Recurrent Entity Network for Anaphora Resolution"
date: 2019-02-05 04:41:55
categories: arXiv_CL
tags: arXiv_CL Language_Model
author: Fei Liu, Luke Zettlemoyer, Jacob Eisenstein
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new architecture for storing and accessing entity mentions during online text processing. While reading the text, entity references are identified, and may be stored by either updating or overwriting a cell in a fixed-length memory. The update operation implies coreference with the other mentions that are stored in the same cell; the overwrite operations causes these mentions to be forgotten. By encoding the memory operations as differentiable gates, it is possible to train the model end-to-end, using both a supervised anaphora resolution objective as well as a supplementary language modeling objective. Evaluation on a dataset of pronoun-name anaphora demonstrates that the model achieves state-of-the-art performance with purely left-to-right processing of the text.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.01541](http://arxiv.org/abs/1902.01541)

##### PDF
[http://arxiv.org/pdf/1902.01541](http://arxiv.org/pdf/1902.01541)

