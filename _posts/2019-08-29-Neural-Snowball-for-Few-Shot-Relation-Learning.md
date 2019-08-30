---
layout: post
title: "Neural Snowball for Few-Shot Relation Learning"
date: 2019-08-29 01:25:52
categories: arXiv_CL
tags: arXiv_CL Knowledge_Graph Knowledge Relation_Extraction Relation
author: Tianyu Gao, Xu Han, Ruobing Xie, Zhiyuan Liu, Fen Lin, Leyu Lin, Maosong Sun
mathjax: true
---

* content
{:toc}

##### Abstract
Knowledge graphs typically undergo open-ended growth of new relations. This cannot be well handled by relation extraction that focuses on pre-defined relations with sufficient training data. To address new relations with few-shot instances, we propose a novel bootstrapping approach, Neural Snowball, to learn new relations by transferring semantic knowledge about existing relations. More specifically, we design Relation Siamese Networks (RelSN) to learn the metric of relational similarities between instances based on existing relations and their labeled data. Afterwards, given a new relation and its few-shot instances, we use RelSN to accumulate reliable instances from unlabeled corpora; these instances are used to train a relation classifier, which can further identify new facts of the new relation. The process is conducted iteratively like a snowball. Experiments show that our model can gather high-quality instances for better few-shot relation learning and achieves significant improvement compared to baselines. Codes and datasets will be released soon.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.11007](http://arxiv.org/abs/1908.11007)

##### PDF
[http://arxiv.org/pdf/1908.11007](http://arxiv.org/pdf/1908.11007)

