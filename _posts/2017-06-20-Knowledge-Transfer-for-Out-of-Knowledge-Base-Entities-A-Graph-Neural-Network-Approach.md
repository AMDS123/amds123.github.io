---
layout: post
title: "Knowledge Transfer for Out-of-Knowledge-Base Entities: A Graph Neural Network Approach"
date: 2017-06-20 01:33:33
categories: arXiv_CL
tags: arXiv_CL Knowledge Embedding
author: Takuo Hamaguchi, Hidekazu Oiwa, Masashi Shimbo, Yuji Matsumoto
mathjax: true
---

* content
{:toc}

##### Abstract
Knowledge base completion (KBC) aims to predict missing information in a knowledge base.In this paper, we address the out-of-knowledge-base (OOKB) entity problem in KBC:how to answer queries concerning test entities not observed at training time. Existing embedding-based KBC models assume that all test entities are available at training time, making it unclear how to obtain embeddings for new entities without costly retraining. To solve the OOKB entity problem without retraining, we use graph neural networks (Graph-NNs) to compute the embeddings of OOKB entities, exploiting the limited auxiliary knowledge provided at test time.The experimental results show the effectiveness of our proposed model in the OOKB setting.Additionally, in the standard KBC setting in which OOKB entities are not involved, our model achieves state-of-the-art performance on the WordNet dataset. The code and dataset are available at this https URL

##### Abstract (translated by Google)
知识库完成（Knowledge Base Completion，KBC）旨在预测知识库中的缺失信息。本文针对知识库中的知识库外的实体问题：如何回答在培训时间没有观察到的测试实体。现有的基于嵌入的KBC模型假设所有测试实体在训练时间都是可用的，使得不清楚如何在没有昂贵的再训练的情况下获得新实体的嵌入。为了解决OOKB实体问题而无需再训练，利用图形神经网络（Graph-NNs）计算OOKB实体的嵌入，利用测试时提供的有限的辅助知识。实验结果表明，本文提出的模型在OOKB另外，在OOKB实体未涉及的标准KBC设置中，我们的模型在WordNet数据集上实现了最新的性能。代码和数据集可在此https URL中获得

##### URL
[https://arxiv.org/abs/1706.05674](https://arxiv.org/abs/1706.05674)

##### PDF
[https://arxiv.org/pdf/1706.05674](https://arxiv.org/pdf/1706.05674)

