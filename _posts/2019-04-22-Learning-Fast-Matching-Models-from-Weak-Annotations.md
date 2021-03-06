---
layout: post
title: "Learning Fast Matching Models from Weak Annotations"
date: 2019-04-22 00:55:00
categories: arXiv_CV
tags: arXiv_CV
author: Xue Li, Zhipeng Luo, Hao Sun, Jianjin Zhang, Weihao Han, Xianqi Chu, Liangjie Zhang, Qi Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a novel training scheme for fast matching models in Search Ads, which is motivated by the real challenges in model training. The first challenge stems from the pursuit of high throughput, which prohibits the deployment of inseparable architectures, and hence greatly limits the model accuracy. The second problem arises from the heavy dependency on human provided labels, which are expensive and time-consuming to collect, yet how to leverage unlabeled search log data is rarely studied. The proposed training framework targets on mitigating both issues, by treating the stronger but undeployable models as annotators, and learning a deployable model from both human provided relevance labels and weakly annotated search log data. Specifically, we first construct multiple auxiliary tasks from the enumerated relevance labels, and train the annotators by jointly learning from those related tasks. The annotation models are then used to assign scores to both labeled and unlabeled training samples. The deployable model is firstly learnt on the scored unlabeled data, and then fine-tuned on scored labeled data, by leveraging both labels and scores via minimizing the proposed label-aware weighted loss. According to our experiments, compared with the baseline that directly learns from relevance labels, training by the proposed framework outperforms it by a large margin, and improves data efficiency substantially by dispensing with 80% labeled samples. The proposed framework allows us to improve the fast matching model by learning from stronger annotators while keeping its architecture unchanged. Meanwhile, our training framework offers a principled manner to leverage search log data in the training phase, which could effectively alleviate our dependency on human provided labels.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1901.10710](https://arxiv.org/abs/1901.10710)

##### PDF
[https://arxiv.org/pdf/1901.10710](https://arxiv.org/pdf/1901.10710)

