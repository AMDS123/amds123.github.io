---
layout: post
title: "Joint Semantic Segmentation and Depth Estimation with Deep Convolutional Networks"
date: 2016-09-19 21:57:28
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Relation
author: Arsalan Mousavian, Hamed Pirsiavash, Jana Kosecka
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-scale deep CNNs have been used successfully for problems mapping each pixel to a label, such as depth estimation and semantic segmentation. It has also been shown that such architectures are reusable and can be used for multiple tasks. These networks are typically trained independently for each task by varying the output layer(s) and training objective. In this work we present a new model for simultaneous depth estimation and semantic segmentation from a single RGB image. Our approach demonstrates the feasibility of training parts of the model for each task and then fine tuning the full, combined model on both tasks simultaneously using a single loss function. Furthermore we couple the deep CNN with fully connected CRF, which captures the contextual relationships and interactions between the semantic and depth cues improving the accuracy of the final results. The proposed model is trained and evaluated on NYUDepth V2 dataset outperforming the state of the art methods on semantic segmentation and achieving comparable results on the task of depth estimation.

##### Abstract (translated by Google)
多尺度深度CNN已被成功地用于将每个像素映射到标签的问题，诸如深度估计和语义分割。这也表明，这样的体系结构是可重用的，可以用于多任务。这些网络通常通过改变输出层和训练目标对每个任务独立地进行训练。在这项工作中，我们提出了一个同时进行深度估计和单个RGB图像的语义分割的新模型。我们的方法证明了对每个任务的模型的部分训练的可行性，然后使用单个丢失函数同时在两个任务上精确调整完整的组合模型。此外，我们还将深层的CNN与完全连接的CRF相结合，CRF捕捉语义和深度线索之间的上下文关系和相互作用，从而提高最终结果的准确性。所提出的模型在NYUDepth V2数据集上进行了训练和评估，优于语义分割领域的现有方法，并在深度估计的任务上取得了可比较的结果。

##### URL
[https://arxiv.org/abs/1604.07480](https://arxiv.org/abs/1604.07480)

##### PDF
[https://arxiv.org/pdf/1604.07480](https://arxiv.org/pdf/1604.07480)

