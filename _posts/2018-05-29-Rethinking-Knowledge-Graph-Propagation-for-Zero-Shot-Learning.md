---
layout: post
title: "Rethinking Knowledge Graph Propagation for Zero-Shot Learning"
date: 2018-05-29 21:55:46
categories: arXiv_CV
tags: arXiv_CV Knowledge_Graph Knowledge Attention Face CNN Relation
author: Michael Kampffmeyer, Yinbo Chen, Xiaodan Liang, Hao Wang, Yujia Zhang, Eric P. Xing
mathjax: true
---

* content
{:toc}

##### Abstract
The potential of graph convolutional neural networks for the task of zero-shot learning has been demonstrated recently. These models are highly sample efficient as related concepts in the graph structure share statistical strength allowing generalization to new classes when faced with a lack of data. However, knowledge from distant nodes can get diluted when propagating through intermediate nodes, because current approaches to zero-shot learning use graph propagation schemes that perform Laplacian smoothing at each layer. We show that extensive smoothing does not help the task of regressing classifier weights in zero-shot learning. In order to still incorporate information from distant nodes and utilize the graph structure, we propose an Attentive Dense Graph Propagation Module (ADGPM). ADGPM allows us to exploit the hierarchical graph structure of the knowledge graph through additional connections. These connections are added based on a node's relationship to its ancestors and descendants and an attention scheme is further used to weigh their contribution depending on the distance to the node. Finally, we illustrate that finetuning of the feature representation after training the ADGPM leads to considerable improvements. Our method achieves competitive results, outperforming previous zero-shot learning approaches.

##### Abstract (translated by Google)
最近已经证明了图卷积神经网络在零点学习任务中的潜力。这些模型具有很高的样本效率，因为图结构中的相关概念共享统计强度，允许在遇到缺乏数据时推广到新类。然而，当通过中间节点传播时，来自远处节点的知识可能会被稀释，因为当前的零射击学习方法使用在每层执行拉普拉斯平滑的图传播方案。我们表明，广泛的平滑不能帮助归零分类器权重的零任务学习任务。为了仍然结合来自遥远节点的信息并利用图结构，我们提出了一个专注密集图传播模块（ADGPM）。 ADGPM允许我们通过附加连接来利用知识图的分层图结构。这些连接是基于节点与其祖先和后代的关系而添加的，并且还使用注意方案根据到节点的距离来衡量它们的贡献。最后，我们说明在ADGPM训练之后对特征表示进行微调可以带来相当大的改进。我们的方法取得了有竞争力的结果，超越了以前的零点学习方法。

##### URL
[https://arxiv.org/abs/1805.11724](https://arxiv.org/abs/1805.11724)

##### PDF
[https://arxiv.org/pdf/1805.11724](https://arxiv.org/pdf/1805.11724)

