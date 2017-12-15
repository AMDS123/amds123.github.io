---
layout: post
title: "Distributed Deep Learning for Question Answering"
date: 2016-08-04 16:41:37
categories: arXiv_CL
tags: arXiv_CL Face Classification Deep_Learning
author: Minwei Feng, Bing Xiang, Bowen Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
This paper is an empirical study of the distributed deep learning for question answering subtasks: answer selection and question classification. Comparison studies of SGD, MSGD, ADADELTA, ADAGRAD, ADAM/ADAMAX, RMSPROP, DOWNPOUR and EASGD/EAMSGD algorithms have been presented. Experimental results show that the distributed framework based on the message passing interface can accelerate the convergence speed at a sublinear scale. This paper demonstrates the importance of distributed training. For example, with 48 workers, a 24x speedup is achievable for the answer selection task and running time is decreased from 138.2 hours to 5.81 hours, which will increase the productivity significantly.

##### Abstract (translated by Google)
本文是对分布式问题回答子任务的深度学习的实证研究：答案选择和问题分类。已经提出了SGD，MSGD，ADADELTA，ADAGRAD，ADAM / ADAMAX，RMSPROP，DOWNPOUR和EASGD / EAMSGD算法的比较研究。实验结果表明，基于消息传递接口的分布式框架能够加快次线性规模下的收敛速度。本文展示了分布式培训的重要性。例如，有48名员工，回答选择任务可实现24倍的加速，运行时间从138.2小时减少到5.81小时，这将显着提高生产率。

##### URL
[https://arxiv.org/abs/1511.01158](https://arxiv.org/abs/1511.01158)

##### PDF
[https://arxiv.org/pdf/1511.01158](https://arxiv.org/pdf/1511.01158)

