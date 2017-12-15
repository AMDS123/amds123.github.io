---
layout: post
title: "Variational methods for Conditional Multimodal Deep Learning"
date: 2016-08-26 10:57:41
categories: arXiv_CV
tags: arXiv_CV Face Deep_Learning Quantitative
author: Gaurav Pandey, Ambedkar Dukkipati
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we address the problem of conditional modality learning, whereby one is interested in generating one modality given the other. While it is straightforward to learn a joint distribution over multiple modalities using a deep multimodal architecture, we observe that such models aren't very effective at conditional generation. Hence, we address the problem by learning conditional distributions between the modalities. We use variational methods for maximizing the corresponding conditional log-likelihood. The resultant deep model, which we refer to as conditional multimodal autoencoder (CMMA), forces the latent representation obtained from a single modality alone to be `close' to the joint representation obtained from multiple modalities. We use the proposed model to generate faces from attributes. We show that the faces generated from attributes using the proposed model, are qualitatively and quantitatively more representative of the attributes from which they were generated, than those obtained by other deep generative models. We also propose a secondary task, whereby the existing faces are modified by modifying the corresponding attributes. We observe that the modifications in face introduced by the proposed model are representative of the corresponding modifications in attributes.

##### Abstract (translated by Google)
在本文中，我们讨论了条件模态学习的问题，即有兴趣在给定另一模态的情况下产生一个模态。虽然使用深度多模式体系结构学习多种模式的联合分布很简单，但我们观察到，这样的模型在条件生成中不是很有效。因此，我们通过学习模式之间的条件分布来解决这个问题。我们使用变分方法来最大化相应的条件对数似然。我们称之为条件多模式自动编码器（CMMA）的最终深层模型，迫使从单一模态获得的潜在表示“接近”从多模态获得的联合表示。我们使用提出的模型来从属性生成面孔。我们表明，使用所提出的模型从属性中产生的面，在定性和定量上比其他深层生成模型所获得的面更能代表产生它们的属性。我们还提出了一个辅助任务，通过修改相应的属性来修改现有的面孔。我们观察到，由所提出的模型引入的面部修改代表了相应的属性修改。

##### URL
[https://arxiv.org/abs/1603.01801](https://arxiv.org/abs/1603.01801)

##### PDF
[https://arxiv.org/pdf/1603.01801](https://arxiv.org/pdf/1603.01801)

