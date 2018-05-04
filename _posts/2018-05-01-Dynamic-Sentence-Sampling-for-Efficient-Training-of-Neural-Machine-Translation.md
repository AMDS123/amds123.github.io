---
layout: post
title: "Dynamic Sentence Sampling for Efficient Training of Neural Machine Translation"
date: 2018-05-01 04:09:09
categories: arXiv_CL
tags: arXiv_CL NMT
author: Rui Wang, Masao Utiyama, Eiichiro Sumita
mathjax: true
---

* content
{:toc}

##### Abstract
Traditional Neural machine translation (NMT) involves a fixed training procedure where each sentence is sampled once during each epoch. In reality, some sentences are well-learned during the initial few epochs; however, using this approach, the well-learned sentences would continue to be trained along with those sentences that were not well learned for 10-30 epochs, which results in a wastage of time. Here, we propose an efficient method to dynamically sample the sentences in order to accelerate the NMT training. In this approach, a weight is assigned to each sentence based on the measured difference between the training costs of two iterations. Further, in each epoch, a certain percentage of sentences are dynamically sampled according to their weights. Empirical results based on the NIST Chinese-to-English and the WMT English-to-German tasks depict that the proposed method can significantly accelerate the NMT training and improve the NMT performance.

##### Abstract (translated by Google)
传统的神经机器翻译（NMT）涉及固定的训练过程，每个句子在每个时期被抽样一次。实际上，在最初的几个时代，一些句子是很好的学习;然而，使用这种方法，学习良好的句子将继续与那些在10-30个时代中学习得不好的句子一起训练，这会导致浪费时间。在这里，我们提出了一种有效的方法来动态地对句子进行抽样以加速NMT训练。在这种方法中，根据两次迭代的训练成本之间测量的差异，为每个句子分配权重。此外，在每个时期，一定比例的句子根据其权重动态采样。基于NIST中英文和WMT英语 - 德语任务的实证结果表明，所提出的方法可以显着加速NMT培训并提高NMT绩效。

##### URL
[https://arxiv.org/abs/1805.00178](https://arxiv.org/abs/1805.00178)

##### PDF
[https://arxiv.org/pdf/1805.00178](https://arxiv.org/pdf/1805.00178)

