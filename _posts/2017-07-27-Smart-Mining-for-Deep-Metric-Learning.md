---
layout: post
title: "Smart Mining for Deep Metric Learning"
date: 2017-07-27 05:27:22
categories: arXiv_CV
tags: arXiv_CV Embedding
author: Ben Harwood, Vijay Kumar B G, Gustavo Carneiro, Ian Reid, Tom Drummond
mathjax: true
---

* content
{:toc}

##### Abstract
To solve deep metric learning problems and producing feature embeddings, current methodologies will commonly use a triplet model to minimise the relative distance between samples from the same class and maximise the relative distance between samples from different classes. Though successful, the training convergence of this triplet model can be compromised by the fact that the vast majority of the training samples will produce gradients with magnitudes that are close to zero. This issue has motivated the development of methods that explore the global structure of the embedding and other methods that explore hard negative/positive mining. The effectiveness of such mining methods is often associated with intractable computational requirements. In this paper, we propose a novel deep metric learning method that combines the triplet model and the global structure of the embedding space. We rely on a smart mining procedure that produces effective training samples for a low computational cost. In addition, we propose an adaptive controller that automatically adjusts the smart mining hyper-parameters and speeds up the convergence of the training process. We show empirically that our proposed method allows for fast and more accurate training of triplet ConvNets than other competing mining methods. Additionally, we show that our method achieves new state-of-the-art embedding results for CUB-200-2011 and Cars196 datasets.

##### Abstract (translated by Google)
为了解决深度量度学习问题和产生特征嵌入，目前的方法将通常使用三元组模型来最小化来自相同类别的样本之间的相对距离，并使得来自不同类别的样本之间的相对距离最大化。虽然成功，但是这个三重模型的训练收敛可能会因为绝大多数训练样本将产生大小接近于零的梯度而受到损害。这个问题激发了探索嵌入的全球结构的方法的发展和其他探索硬性负面/正面挖掘的方法。这种挖掘方法的有效性通常与难以处理的计算要求相关联。在本文中，我们提出了一种结合三重模型和嵌入空间全局结构的深度度量学习方法。我们依靠一个聪明的开采程序，以低的计算成本生产有效的训练样本。另外，我们提出了一种自适应控制器，自动调整智能挖掘超参数，加快训练过程的收敛速度。我们经验地显示，我们提出的方法允许快速和更准确的三联ConvNets培训比其他竞争采矿方法。另外，我们展示了我们的方法为CUB-200-2011和Cars196数据集实现了最新的最新嵌入结果。

##### URL
[https://arxiv.org/abs/1704.01285](https://arxiv.org/abs/1704.01285)

##### PDF
[https://arxiv.org/pdf/1704.01285](https://arxiv.org/pdf/1704.01285)

