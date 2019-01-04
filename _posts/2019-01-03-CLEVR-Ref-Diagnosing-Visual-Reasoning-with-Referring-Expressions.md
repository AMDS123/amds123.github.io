---
layout: post
title: "CLEVR-Ref+: Diagnosing Visual Reasoning with Referring Expressions"
date: 2019-01-03 18:58:06
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge Segmentation Quantitative Detection VQA
author: Runtao Liu, Chenxi Liu, Yutong Bai, Alan Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
Referring object detection and referring image segmentation are important tasks that require joint understanding of visual information and natural language. Yet there has been evidence that current benchmark datasets suffer from bias, and current state-of-the-art models cannot be easily evaluated on their intermediate reasoning process. To address these issues and complement similar efforts in visual question answering, we build CLEVR-Ref+, a synthetic diagnostic dataset for referring expression comprehension. The precise locations and attributes of the objects are readily available, and the referring expressions are automatically associated with functional programs. The synthetic nature allows control over dataset bias (through sampling strategy), and the modular programs enable intermediate reasoning ground truth without human annotators. 
 In addition to evaluating several state-of-the-art models on CLEVR-Ref+, we also propose IEP-Ref, a module network approach that significantly outperforms other models on our dataset. In particular, we present two interesting and important findings using IEP-Ref: (1) the module trained to transform feature maps into segmentation masks can be attached to any intermediate module to reveal the entire reasoning process step-by-step; (2) even if all training data has at least one object referred, IEP-Ref can correctly predict no-foreground when presented with false-premise referring expressions. To the best of our knowledge, this is the first direct and quantitative proof that neural modules behave in the way they are intended.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.00850](http://arxiv.org/abs/1901.00850)

##### PDF
[http://arxiv.org/pdf/1901.00850](http://arxiv.org/pdf/1901.00850)

