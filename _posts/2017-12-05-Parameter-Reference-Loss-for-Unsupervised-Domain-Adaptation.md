---
layout: post
title: 'Parameter Reference Loss for Unsupervised Domain Adaptation'
date: 2017-12-05 10:19:34
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Jiren Jin, Richard G. Calland, Takeru Miyato, Brian K. Vogel, Hideki Nakayama
---

* content
{:toc}

##### Abstract
The success of deep learning in computer vision is mainly attributed to an abundance of data. However, collecting large-scale data is not always possible, especially for the supervised labels. Unsupervised domain adaptation (UDA) aims to utilize labeled data from a source domain to learn a model that generalizes to a target domain of unlabeled data. A large amount of existing work uses Siamese network-based models, where two streams of neural networks process the source and the target domain data respectively. Nevertheless, most of these approaches focus on minimizing the domain discrepancy, overlooking the importance of preserving the discriminative ability for target domain features. Another important problem in UDA research is how to evaluate the methods properly. Common evaluation procedures require target domain labels for hyper-parameter tuning and model selection, contradicting the definition of the UDA task. Hence we propose a more reasonable evaluation principle that avoids this contradiction by simply adopting the latest snapshot of a model for evaluation. This adds an extra requirement for UDA methods besides the main performance criteria: the stability during training. We design a novel method that connects the target domain stream to the source domain stream with a Parameter Reference Loss (PRL) to solve these problems simultaneously. Experiments on various datasets show that the proposed PRL not only improves the performance on the target domain, but also stabilizes the training procedure. As a result, PRL based models do not need the contradictory model selection, and thus are more suitable for practical applications.

##### Abstract (translated by Google)
计算机视觉深度学习的成功主要是由于数据丰富。然而，收集大规模数据并不总是可能的，特别是对于监督标签。无监督域适应（UDA）旨在利用来源域的标记数据来学习推广到未标记数据目标域的模型。大量现有的工作使用连体网络模型，其中两个神经网络流分别处理源和目标域数据。尽管如此，这些方法大多集中于最小化领域差异，忽略了保留目标领域特征的区分能力的重要性。 UDA研究的另一个重要问题是如何正确评估方法。通用评估程序要求目标域标签用于超参数调整和模型选择，这与UDA任务的定义相矛盾。因此，我们提出一个更合理的评估原则，通过简单地采用评估模型的最新快照来避免这个矛盾。除了主要的性能标准之外，这为UDA方法增加了额外的要求：培训期间的稳定性。我们设计了一种新的方法，通过参数引用丢失（PRL）将目标域流连接到源域流，以同时解决这些问题。在各种数据集上的实验表明，所提出的PRL不仅提高了目标域的性能，而且稳定了训练过程。因此，基于PRL的模型不需要相互矛盾的模型选择，因此更适合于实际应用。

##### URL
[http://arxiv.org/abs/1711.07170](http://arxiv.org/abs/1711.07170)

