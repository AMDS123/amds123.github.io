---
layout: post
title: "Cross-domain Human Parsing via Adversarial Feature and Label Adaptation"
date: 2018-01-04 06:55:59
categories: arXiv_CV
tags: arXiv_CV Adversarial Relation
author: Si Liu, Yao Sun, Defa Zhu, Guanghui Ren, Yu Chen, Jiashi Feng, Jizhong Han
mathjax: true
---

* content
{:toc}

##### Abstract
Human parsing has been extensively studied recently due to its wide applications in many important scenarios. Mainstream fashion parsing models focus on parsing the high-resolution and clean images. However, directly applying the parsers trained on benchmarks to a particular application scenario in the wild, e.g., a canteen, airport or workplace, often gives non-satisfactory performance due to domain shift. In this paper, we explore a new and challenging cross-domain human parsing problem: taking the benchmark dataset with extensive pixel-wise labeling as the source domain, how to obtain a satisfactory parser on a new target domain without requiring any additional manual labeling? To this end, we propose a novel and efficient cross-domain human parsing model to bridge the cross-domain differences in terms of visual appearance and environment conditions and fully exploit commonalities across domains. Our proposed model explicitly learns a feature compensation network, which is specialized for mitigating the cross-domain differences. A discriminative feature adversarial network is introduced to supervise the feature compensation to effectively reduce the discrepancy between feature distributions of two domains. Besides, our model also introduces a structured label adversarial network to guide the parsing results of the target domain to follow the high-order relationships of the structured labels shared across domains. The proposed framework is end-to-end trainable, practical and scalable in real applications. Extensive experiments are conducted where LIP dataset is the source domain and 4 different datasets including surveillance videos, movies and runway shows are evaluated as target domains. The results consistently confirm data efficiency and performance advantages of the proposed method for the cross-domain human parsing problem.

##### Abstract (translated by Google)
由于在许多重要情况下的广泛应用，人类解析近来被广泛研究。主流时尚解析模型专注于解析高分辨率和清晰的图像。然而，将在基准上训练的解析器直接应用于野外（例如食堂，机场或工作场所）的特定应用场景通常由于域转移而导致不令人满意的性能。在本文中，我们探索了一个新的和具有挑战性的跨域人类解析问题：以广泛的像素标签作为源域的基准数据集，如何获得满意的解析器在新的目标域上，而不需要任何额外的手动标记？为此，我们提出了一种新颖高效的跨域人类解析模型，以跨越视觉外观和环境条件的跨领域差异，充分利用跨领域的共性。我们提出的模型明确地学习了一个专门用于缓解跨域差异的特征补偿网络。引入判别特征对抗网络来监督特征补偿，有效减少两域特征分布的差异。此外，我们的模型还引入了一个结构化的标签对抗网络来指导目标域的解析结果遵循跨域共享的结构化标签的高阶关系。所提出的框架是端到端的可训练的，实际的并且在实际应用中可扩展。在LIP数据集是源域的情况下进行了大量实验，并且将包括监视视频，电影和跑道展示在内的4个不同数据集评估为目标域。结果一致证实了该方法对于跨域人解析问题的数据效率和性能优势。

##### URL
[http://arxiv.org/abs/1801.01260](http://arxiv.org/abs/1801.01260)

##### PDF
[http://arxiv.org/pdf/1801.01260](http://arxiv.org/pdf/1801.01260)

