---
layout: post
title: "Semantic Object Parsing with Graph LSTM"
date: 2016-03-23 03:31:02
categories: arXiv_CV
tags: arXiv_CV Optimization RNN Relation
author: Xiaodan Liang, Xiaohui Shen, Jiashi Feng, Liang Lin, Shuicheng Yan
mathjax: true
---

* content
{:toc}

##### Abstract
By taking the semantic object parsing task as an exemplar application scenario, we propose the Graph Long Short-Term Memory (Graph LSTM) network, which is the generalization of LSTM from sequential data or multi-dimensional data to general graph-structured data. Particularly, instead of evenly and fixedly dividing an image to pixels or patches in existing multi-dimensional LSTM structures (e.g., Row, Grid and Diagonal LSTMs), we take each arbitrary-shaped superpixel as a semantically consistent node, and adaptively construct an undirected graph for each image, where the spatial relations of the superpixels are naturally used as edges. Constructed on such an adaptive graph topology, the Graph LSTM is more naturally aligned with the visual patterns in the image (e.g., object boundaries or appearance similarities) and provides a more economical information propagation route. Furthermore, for each optimization step over Graph LSTM, we propose to use a confidence-driven scheme to update the hidden and memory states of nodes progressively till all nodes are updated. In addition, for each node, the forgets gates are adaptively learned to capture different degrees of semantic correlation with neighboring nodes. Comprehensive evaluations on four diverse semantic object parsing datasets well demonstrate the significant superiority of our Graph LSTM over other state-of-the-art solutions.

##### Abstract (translated by Google)
通过将语义对象解析任务作为一个典型的应用场景，提出了图形长期短期记忆（Graph LSTM）网络，它是LSTM从时序数据或多维数据到一般图形结构数据的推广。特别地，不是将图像均匀地固定地分割成现有的多维LSTM结构（例如，行，栅格和对角线LSTM）中的像素或贴片，而是将每个任意形状的超像素作为语义上一致的节点，并自适应地构建无向对于每个图像，其中超像素的空间关系自然被用作边缘。构建在这样的自适应图拓扑上，图LSTM更自然地与图像中的视觉图案（例如，对象边界或外观相似性）对齐，并提供更经济的信息传播路线。此外，对于图LSTM的每个优化步骤，我们建议使用置信度驱动方案逐步更新节点的隐藏和内存状态，直到更新所有节点。另外，对于每个节点，自适应门都被自适应学习，以捕获与相邻节点的不同程度的语义相关性。对四种不同的语义对象分析数据集进行全面的评估，充分证明了我们的Graph LSTM优于其他最先进的解决方案。

##### URL
[https://arxiv.org/abs/1603.07063](https://arxiv.org/abs/1603.07063)

##### PDF
[https://arxiv.org/pdf/1603.07063](https://arxiv.org/pdf/1603.07063)

