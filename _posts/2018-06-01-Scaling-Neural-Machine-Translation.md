---
layout: post
title: "Scaling Neural Machine Translation"
date: 2018-06-01 04:33:16
categories: arXiv_CL
tags: arXiv_CL
author: Myle Ott, Sergey Edunov, David Grangier, Michael Auli
mathjax: true
---

* content
{:toc}

##### Abstract
Sequence to sequence learning models still require several days to reach state of the art performance on large benchmark datasets using a single machine. This paper shows that reduced precision and large batch training can speedup training by nearly 5x on a single 8-GPU machine with careful tuning and implementation. On WMT'14 English-German translation, we match the accuracy of (Vaswani et al 2017) in under 5 hours when training on 8 GPUs and we obtain a new state of the art of 29.3 BLEU after training for 91 minutes on 128 GPUs. We further improve these results to 29.8 BLEU by training on the much larger Paracrawl dataset.

##### Abstract (translated by Google)
序列学习模型的序列仍然需要数天的时间才能使用单台机器在大型基准数据集上实现最先进的性能。本文表明，通过仔细调整和实施，降低精度和大批量训练可以在单个8 GPU计算机上将训练速度提高近5倍。在WMT'14英文 - 德文翻译中，我们在5个小时内匹配（Vaswani et al 2017）的准确性，在8个GPU上训练，我们在128个GPU上训练了91分钟后获得了29.3 BLEU的最新技术水平。我们通过对更大的Paracrawl数据集进行培训，将这些结果进一步提高到29.8 BLEU。

##### URL
[http://arxiv.org/abs/1806.00187](http://arxiv.org/abs/1806.00187)

##### PDF
[http://arxiv.org/pdf/1806.00187](http://arxiv.org/pdf/1806.00187)

