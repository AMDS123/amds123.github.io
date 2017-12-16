---
layout: post
title: "Deep Sketch Hashing: Fast Free-hand Sketch-Based Image Retrieval"
date: 2017-03-16 13:18:36
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Knowledge CNN Relation
author: Li Liu, Fumin Shen, Yuming Shen, Xianglong Liu, Ling Shao
mathjax: true
---

* content
{:toc}

##### Abstract
Free-hand sketch-based image retrieval (SBIR) is a specific cross-view retrieval task, in which queries are abstract and ambiguous sketches while the retrieval database is formed with natural images. Work in this area mainly focuses on extracting representative and shared features for sketches and natural images. However, these can neither cope well with the geometric distortion between sketches and images nor be feasible for large-scale SBIR due to the heavy continuous-valued distance computation. In this paper, we speed up SBIR by introducing a novel binary coding method, named \textbf{Deep Sketch Hashing} (DSH), where a semi-heterogeneous deep architecture is proposed and incorporated into an end-to-end binary coding framework. Specifically, three convolutional neural networks are utilized to encode free-hand sketches, natural images and, especially, the auxiliary sketch-tokens which are adopted as bridges to mitigate the sketch-image geometric distortion. The learned DSH codes can effectively capture the cross-view similarities as well as the intrinsic semantic correlations between different categories. To the best of our knowledge, DSH is the first hashing work specifically designed for category-level SBIR with an end-to-end deep architecture. The proposed DSH is comprehensively evaluated on two large-scale datasets of TU-Berlin Extension and Sketchy, and the experiments consistently show DSH's superior SBIR accuracies over several state-of-the-art methods, while achieving significantly reduced retrieval time and memory footprint.

##### Abstract (translated by Google)
基于草图的自由图像检索（SBIR）是一种特殊的跨视图检索任务，其中查询是抽象的和模糊的草图，而检索数据库是由自然图像构成的。这方面的工作主要集中在提取草图和自然图像的代表性和共享特征。然而，由于大量的连续值距离计算，这些既不能很好地处理草图和图像之间的几何失真，也不能适用于大规模的SBIR。在本文中，我们通过引入一种名为\ textbf {Deep Sketch Hashing}（DSH）的新型二进制编码方法来加速SBIR，其中提出了半异构深度架构并将其并入到端到端二进制编码框架中。具体而言，利用三个卷积神经网络对自由手绘草图，自然图像，特别是作为桥梁采用的辅助草图标记进行编码，以缓解草图几何变形。学习的DSH代码可以有效地捕捉到不同类别之间的交叉视图相似性和内在语义相关性。就我们所知，DSH是第一个专门为具有端到端深度架构的类别级SBIR设计的哈希工作。所提出的DSH在TU-Berlin Extension和Sketchy的两个大规模数据集上进行了全面评估，实验结果一致显示了DSH在多种最先进方法上的卓越SBIR精度，同时显着缩短了检索时间和内存占用。

##### URL
[https://arxiv.org/abs/1703.05605](https://arxiv.org/abs/1703.05605)

##### PDF
[https://arxiv.org/pdf/1703.05605](https://arxiv.org/pdf/1703.05605)

