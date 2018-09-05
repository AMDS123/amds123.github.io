---
layout: post
title: "Dual Conditional Cross-Entropy Filtering of Noisy Parallel Corpora"
date: 2018-09-01 14:38:16
categories: arXiv_CL
tags: arXiv_CL
author: Marcin Junczys-Dowmunt
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we introduce dual conditional cross-entropy filtering for noisy parallel data. For each sentence pair of the noisy parallel corpus we compute cross-entropy scores according to two inverse translation models trained on clean data. We penalize divergent cross-entropies and weigh the penalty by the cross-entropy average of both models. Sorting or thresholding according to these scores results in better subsets of parallel data. We achieve higher BLEU scores with models trained on parallel data filtered only from Paracrawl than with models trained on clean WMT data. We further evaluate our method in the context of the WMT2018 shared task on parallel corpus filtering and achieve the overall highest ranking scores of the shared task, scoring top in three out of four subtasks.

##### Abstract (translated by Google)
在这项工作中，我们为噪声并行数据引入双条件交叉熵滤波。对于噪声平行语料库的每个句子对，我们根据在清洁数据上训练的两个逆转换模型计算交叉熵分数。我们惩罚不同的交叉熵，并用两种模型的交叉熵平均值来衡量惩罚。根据这些分数进行排序或阈值处理可以得到更好的并行数据子集。我们使用仅从Paracrawl过滤的并行数据训练模型获得更高的BLEU分数，而不是使用干净WMT数据训练的模型。我们在WMT2018并行语料库过滤共享任务的上下文中进一步评估我们的方法，并实现共享任务的总体最高排名分数，在四个子任务中的三个中得分最高。

##### URL
[http://arxiv.org/abs/1809.00197](http://arxiv.org/abs/1809.00197)

##### PDF
[http://arxiv.org/pdf/1809.00197](http://arxiv.org/pdf/1809.00197)

