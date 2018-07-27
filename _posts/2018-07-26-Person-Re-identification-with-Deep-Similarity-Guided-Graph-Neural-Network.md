---
layout: post
title: "Person Re-identification with Deep Similarity-Guided Graph Neural Network"
date: 2018-07-26 06:56:51
categories: arXiv_CV
tags: arXiv_CV Re-identification Person_Re-identification Deep_Learning Prediction Relation
author: Yantao Shen, Hongsheng Li, Shuai Yi, Dapeng Chen, Xiaogang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
The person re-identification task requires to robustly estimate visual similarities between person images. However, existing person re-identification models mostly estimate the similarities of different image pairs of probe and gallery images independently while ignores the relationship information between different probe-gallery pairs. As a result, the similarity estimation of some hard samples might not be accurate. In this paper, we propose a novel deep learning framework, named Similarity-Guided Graph Neural Network (SGGNN) to overcome such limitations. Given a probe image and several gallery images, SGGNN creates a graph to represent the pairwise relationships between probe-gallery pairs (nodes) and utilizes such relationships to update the probe-gallery relation features in an end-to-end manner. Accurate similarity estimation can be achieved by using such updated probe-gallery relation features for prediction. The input features for nodes on the graph are the relation features of different probe-gallery image pairs. The probe-gallery relation feature updating is then performed by the messages passing in SGGNN, which takes other nodes' information into account for similarity estimation. Different from conventional GNN approaches, SGGNN learns the edge weights with rich labels of gallery instance pairs directly, which provides relation fusion more precise information. The effectiveness of our proposed method is validated on three public person re-identification datasets.

##### Abstract (translated by Google)
人员重新识别任务需要稳健地估计人物图像之间的视觉相似性。然而，现有的人重新识别模型主要是独立地估计探针和图库图像的不同图像对的相似性，而忽略了不同探针 - 图库对之间的关​​系信息。结果，一些硬样本的相似性估计可能不准确。在本文中，我们提出了一种新的深度学习框架，命名为相似性引导图神经网络（SGGNN）来克服这些局限性。给定探测图像和多个图库图像，SGGNN创建一个图形来表示探测 - 图库对（节点）之间的成对关系，并利用这种关系以端到端的方式更新探测 - 图库关系特征。通过使用这种更新的探针 - 图库关系特征进行预测，可以实现精确的相似性估计。图上节点的输入特征是不同探针 - 图库对的关系特征。然后，通过SGGNN中传递的消息执行探测 - 图库关系特征更新，其将其他节点的信息考虑用于相似性估计。与传统的GNN方法不同，SGGNN直接利用图库实例对的丰富标签来学习边缘权重，从而为关系融合提供更精确的信息。我们提出的方法的有效性在三个公共人员重新识别数据集上得到验证。

##### URL
[http://arxiv.org/abs/1807.09975](http://arxiv.org/abs/1807.09975)

##### PDF
[http://arxiv.org/pdf/1807.09975](http://arxiv.org/pdf/1807.09975)

