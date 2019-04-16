---
layout: post
title: "Ensemble Distillation for Neural Machine Translation"
date: 2017-08-08 01:41:25
categories: arXiv_CL
tags: arXiv_CL Knowledge NMT
author: Markus Freitag, Yaser Al-Onaizan, Baskaran Sankaran
mathjax: true
---

* content
{:toc}

##### Abstract
Knowledge distillation describes a method for training a student network to perform better by learning from a stronger teacher network. Translating a sentence with an Neural Machine Translation (NMT) engine is time expensive and having a smaller model speeds up this process. We demonstrate how to transfer the translation quality of an ensemble and an oracle BLEU teacher network into a single NMT system. Further, we present translation improvements from a teacher network that has the same architecture and dimensions of the student network. As the training of the student model is still expensive, we introduce a data filtering method based on the knowledge of the teacher model that not only speeds up the training, but also leads to better translation quality. Our techniques need no code change and can be easily reproduced with any NMT architecture to speed up the decoding process.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1702.01802](https://arxiv.org/abs/1702.01802)

##### PDF
[https://arxiv.org/pdf/1702.01802](https://arxiv.org/pdf/1702.01802)

