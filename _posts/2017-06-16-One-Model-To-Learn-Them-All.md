---
layout: post
title: "One Model To Learn Them All"
date: 2017-06-16 03:10:03
categories: arXiv_CV
tags: arXiv_CV Image_Caption Sparse Attention Speech_Recognition Caption CNN Image_Classification Classification Deep_Learning Recognition
author: Lukasz Kaiser, Aidan N. Gomez, Noam Shazeer, Ashish Vaswani, Niki Parmar, Llion Jones, Jakob Uszkoreit
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning yields great results across many fields, from speech recognition, image classification, to translation. But for each problem, getting a deep model to work well involves research into the architecture and a long period of tuning. We present a single model that yields good results on a number of problems spanning multiple domains. In particular, this single model is trained concurrently on ImageNet, multiple translation tasks, image captioning (COCO dataset), a speech recognition corpus, and an English parsing task. Our model architecture incorporates building blocks from multiple domains. It contains convolutional layers, an attention mechanism, and sparsely-gated layers. Each of these computational blocks is crucial for a subset of the tasks we train on. Interestingly, even if a block is not crucial for a task, we observe that adding it never hurts performance and in most cases improves it on all tasks. We also show that tasks with less data benefit largely from joint training with other tasks, while performance on large tasks degrades only slightly if at all.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1706.05137](https://arxiv.org/abs/1706.05137)

##### PDF
[https://arxiv.org/pdf/1706.05137](https://arxiv.org/pdf/1706.05137)

