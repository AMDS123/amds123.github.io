---
layout: post
title: "CASED: Curriculum Adaptive Sampling for Extreme Data Imbalance"
date: 2018-07-27 20:10:11
categories: arXiv_CV
tags: arXiv_CV Segmentation Optimization Deep_Learning Detection
author: Andrew Jesson, Nicolas Guizard, Sina Hamidi Ghalehjegh, Damien Goblot, Florian Soudan, Nicolas Chapados
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce CASED, a novel curriculum sampling algorithm that facilitates the optimization of deep learning segmentation or detection models on data sets with extreme class imbalance. We evaluate the CASED learning framework on the task of lung nodule detection in chest CT. In contrast to two-stage solutions, wherein nodule candidates are first proposed by a segmentation model and refined by a second detection stage, CASED improves the training of deep nodule segmentation models (e.g. UNet) to the point where state of the art results are achieved using only a trivial detection stage. CASED improves the optimization of deep segmentation models by allowing them to first learn how to distinguish nodules from their immediate surroundings, while continuously adding a greater proportion of difficult-to-classify global context, until uniformly sampling from the empirical data distribution. Using CASED during training yields a minimalist proposal to the lung nodule detection problem that tops the LUNA16 nodule detection benchmark with an average sensitivity score of 88.35%. Furthermore, we find that models trained using CASED are robust to nodule annotation quality by showing that comparable results can be achieved when only a point and radius for each ground truth nodule are provided during training. Finally, the CASED learning framework makes no assumptions with regard to imaging modality or segmentation target and should generalize to other medical imaging problems where class imbalance is a persistent problem.

##### Abstract (translated by Google)
我们介绍了CASED，这是一种新颖的课程抽样算法，有助于优化深度学习分割或检测具有极端不平衡性的数据集模型。我们评估CASED学习框架对胸部CT肺结节检测的任务。与两阶段解决方案相比，其中结节候选者首先通过分割模型提出并通过第二检测阶段进行细化，CASED改进了深部结节分割模型（例如UNet）的训练，达到了达到最先进结果的程度。仅使用一个简单的检测阶段。 CASED通过允许他们首先学习如何区分结节与其周围环境，同时不断添加更大比例的难以分类的全局背景来改进深度分割模型的优化，直到从经验数据分布中均匀采样。在训练期间使用CASED产生了对肺结节检测问题的极简主义建议，该问题高于LUNA16结节检测基准，平均灵敏度得分为88.35％。此外，我们发现使用CASED训练的模型对于结节注释质量是稳健的，表明当在训练期间仅提供每个地面实况结节的点和半径时可以实现可比较的结果。最后，CASED学习框架不对成像模态或分割目标做出任何假设，并且应该推广到其中类不平衡是持久性问题的其他医学成像问题。

##### URL
[http://arxiv.org/abs/1807.10819](http://arxiv.org/abs/1807.10819)

##### PDF
[http://arxiv.org/pdf/1807.10819](http://arxiv.org/pdf/1807.10819)

