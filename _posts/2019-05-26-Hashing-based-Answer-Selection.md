---
layout: post
title: "Hashing based Answer Selection"
date: 2019-05-26 03:33:42
categories: arXiv_CL
tags: arXiv_CL QA Attention Prediction
author: Dong Xu, Wu-Jun Li
mathjax: true
---

* content
{:toc}

##### Abstract
Answer selection is an important subtask of question answering (QA), where deep models usually achieve better performance. Most deep models adopt question-answer interaction mechanisms, such as attention, to get vector representations for answers. When these interaction based deep models are deployed for online prediction, the representations of all answers need to be recalculated for each question. This procedure is time-consuming for deep models with complex encoders like BERT which usually have better accuracy than simple encoders. One possible solution is to store the matrix representation (encoder output) of each answer in memory to avoid recalculation. But this will bring large memory cost. In this paper, we propose a novel method, called hashing based answer selection (HAS), to tackle this problem. HAS adopts a hashing strategy to learn a binary matrix representation for each answer, which can dramatically reduce the memory cost for storing the matrix representations of answers. Hence, HAS can adopt complex encoders like BERT in the model, but the online prediction of HAS is still fast with a low memory cost. Experimental results on three popular answer selection datasets show that HAS can outperform existing models to achieve state-of-the-art performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.10718](http://arxiv.org/abs/1905.10718)

##### PDF
[http://arxiv.org/pdf/1905.10718](http://arxiv.org/pdf/1905.10718)

