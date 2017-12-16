---
layout: post
title: "Identifying Spatial Relations in Images using Convolutional Neural Networks"
date: 2017-06-13 18:24:11
categories: arXiv_CV
tags: arXiv_CV Knowledge_Graph Knowledge CNN Prediction Relation
author: Mandar Haldekar, Ashwinkumar Ganesan, Tim Oates
mathjax: true
---

* content
{:toc}

##### Abstract
Traditional approaches to building a large scale knowledge graph have usually relied on extracting information (entities, their properties, and relations between them) from unstructured text (e.g. Dbpedia). Recent advances in Convolutional Neural Networks (CNN) allow us to shift our focus to learning entities and relations from images, as they build robust models that require little or no pre-processing of the images. In this paper, we present an approach to identify and extract spatial relations (e.g., The girl is standing behind the table) from images using CNNs. Our research addresses two specific challenges: providing insight into how spatial relations are learned by the network and which parts of the image are used to predict these relations. We use the pre-trained network VGGNet to extract features from an image and train a Multi-layer Perceptron (MLP) on a set of synthetic images and the sun09 dataset to extract spatial relations. The MLP predicts spatial relations without a bounding box around the objects or the space in the image depicting the relation. To understand how the spatial relations are represented in the network, a heatmap is overlayed on the image to show the regions that are deemed important by the network. Also, we analyze the MLP to show the relationship between the activation of consistent groups of nodes and the prediction of a spatial relation. We show how the loss of these groups affects the networks ability to identify relations.

##### Abstract (translated by Google)
传统的构建大规模知识图的方法通常依赖于从非结构化文本（如Dbpedia）中提取信息（实体，属性以及它们之间的关系）。卷积神经网络（CNN）的最新进展使得我们可以将我们的注意力从图像转移到学习实体和关系上，因为它们构建的鲁棒模型只需要很少或不需要对图像进行预处理。在本文中，我们提出了一种从CNN图像中识别和提取空间关系的方法（例如，女孩站在桌子后面）。我们的研究解决了两个具体的挑战：提供洞察如何空间关系是由网络学习和图像的哪些部分被用来预测这些关系。我们使用预先训练的网络VGGNet从图像中提取特征，并在一组合成图像上训练多层感知器（MLP），并使用sun09数据集提取空间关系。 MLP预测空间关系，没有围绕对象的边界框或描绘关系的图像中的空间。为了理解网络中的空间关系是如何表现的，在图像上覆盖一个热图，以显示网络认为重要的区域。同时，我们分析MLP来展示一致节点组的激活与空间关系的预测之间的关系。我们展示了这些群体的损失如何影响网络识别关系的能力。

##### URL
[https://arxiv.org/abs/1706.04215](https://arxiv.org/abs/1706.04215)

##### PDF
[https://arxiv.org/pdf/1706.04215](https://arxiv.org/pdf/1706.04215)

