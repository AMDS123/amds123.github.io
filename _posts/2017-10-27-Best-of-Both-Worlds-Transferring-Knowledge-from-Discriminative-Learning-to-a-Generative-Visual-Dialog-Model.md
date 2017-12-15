---
layout: post
title: "Best of Both Worlds: Transferring Knowledge from Discriminative Learning to a Generative Visual Dialog Model"
date: 2017-10-27 20:27:07
categories: arXiv_CL
tags: arXiv_CL Adversarial Knowledge Attention RNN
author: Jiasen Lu, Anitha Kannan, Jianwei Yang, Devi Parikh, Dhruv Batra
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel training framework for neural sequence models, particularly for grounded dialog generation. The standard training paradigm for these models is maximum likelihood estimation (MLE), or minimizing the cross-entropy of the human responses. Across a variety of domains, a recurring problem with MLE trained generative neural dialog models (G) is that they tend to produce 'safe' and generic responses ("I don't know", "I can't tell"). In contrast, discriminative dialog models (D) that are trained to rank a list of candidate human responses outperform their generative counterparts; in terms of automatic metrics, diversity, and informativeness of the responses. However, D is not useful in practice since it cannot be deployed to have real conversations with users. Our work aims to achieve the best of both worlds -- the practical usefulness of G and the strong performance of D -- via knowledge transfer from D to G. Our primary contribution is an end-to-end trainable generative visual dialog model, where G receives gradients from D as a perceptual (not adversarial) loss of the sequence sampled from G. We leverage the recently proposed Gumbel-Softmax (GS) approximation to the discrete distribution -- specifically, an RNN augmented with a sequence of GS samplers, coupled with the straight-through gradient estimator to enable end-to-end differentiability. We also introduce a stronger encoder for visual dialog, and employ a self-attention mechanism for answer encoding along with a metric learning loss to aid D in better capturing semantic similarities in answer responses. Overall, our proposed model outperforms state-of-the-art on the VisDial dataset by a significant margin (2.67% on recall@10). The source code can be downloaded from this https URL

##### Abstract (translated by Google)
我们提出了一个新的神经序列模型的训练框架，特别是基于接口的对话生成。这些模型的标准训练范例是最大似然估计（MLE），或最小化人类反应的交叉熵。在多种领域中，MLE训练生成神经对话模型（G）的一个反复出现的问题是，它们倾向于产生“安全”和通用的反应（“我不知道”，“我不知道”）。相比之下，区分对话模型（D）被训练以排列候选人类反应列表胜过其生成对应物;在自动度量，多样性和信息的答复方面。然而，D在实践中并不实用，因为它不能被部署到与用户进行真正的对话。我们的工作旨在通过从D到G的知识转移实现两全其美--G的实际有用性和D的强大性能。我们的主要贡献是端到端的可训练生成性视觉对话模型，其中G从D接收梯度作为从G采样的序列的感知（而不是对抗）损失。我们利用最近提出的离散分布的Gumbel-Softmax（GS）近似 - 具体地，用一系列GS采样器增强的RNN，再加上直通梯度估计器，以实现端到端的可微性。我们还引入了一个更强大的视觉对话编码器，并采用自我注意机制进行应答编码以及度量学习损失，以帮助D更好地捕捉应答响应中的语义相似性。总的来说，我们提出的模型在VisDial数据集上的表现优于现有技术（占回收率10％的2.67％）。源代码可以从这个https URL下载

##### URL
[https://arxiv.org/abs/1706.01554](https://arxiv.org/abs/1706.01554)

##### PDF
[https://arxiv.org/pdf/1706.01554](https://arxiv.org/pdf/1706.01554)

