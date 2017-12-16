---
layout: post
title: "Soft Correspondences in Multimodal Scene Parsing"
date: 2017-09-28 08:08:11
categories: arXiv_CV
tags: arXiv_CV Inference
author: Sarah Taghavi Namin, Mohammad Najafi, Mathieu Salzmann, Lars Petersson
mathjax: true
---

* content
{:toc}

##### Abstract
Exploiting multiple modalities for semantic scene parsing has been shown to improve accuracy over the singlemodality scenario. However multimodal datasets often suffer from problems such as data misalignment and label inconsistencies, where the existing methods assume that corresponding regions in two modalities must have identical labels. We propose to address this issue, by formulating multimodal semantic labeling as inference in a CRF and introducing latent nodes to explicitly model inconsistencies between two modalities. These latent nodes allow us not only to leverage information from both domains to improve their labeling, but also to cut the edges between inconsistent regions. We propose to learn intradomain and inter-domain potential functions from training data to avoid hand-tuning of the model parameters. We evaluate our approach on two publicly available datasets containing 2D and 3D data. Thanks to our latent nodes and our learning strategy, our method outperforms the state-of-the-art in both cases. Moreover, in order to highlight the benefits of the geometric information and the potential of our method in simultaneous 2D/3D semantic and geometric inference, we performed simultaneous inference of semantic and geometric classes both in 2D and 3D that led to satisfactory improvements of the labeling results in both datasets.

##### Abstract (translated by Google)
已经显示，利用多种语义场景解析模式可以提高单一模式场景的准确性。然而，多模式数据集经常遇到诸如数据错位和标签不一致等问题，现有方法假定两种模式中的相应区域必须具有相同的标签。我们建议解决这个问题，通过制定多模态语义标签作为CRF的推论，并引入潜在的节点明确建模两种模式之间的不一致。这些潜在的节点使我们不仅可以利用这两个领域的信息来改善它们的标签，而且还可以削减不一致区域之间的边界。我们建议从训练数据中学习域内和域间的潜在函数，以避免手动调整模型参数。我们在包含二维和三维数据的两个公开可用的数据集上评估我们的方法。由于我们的潜在节点和我们的学习策略，我们的方法在两种情况下均优于现有技术。此外，为了突出几何信息的优势和我们的方法在同时进行2D / 3D语义和几何推理中的潜力，我们对2D和3D中的语义类和几何类进行了同时推理，导致标签的令人满意的改进导致两个数据集。

##### URL
[https://arxiv.org/abs/1709.09843](https://arxiv.org/abs/1709.09843)

##### PDF
[https://arxiv.org/pdf/1709.09843](https://arxiv.org/pdf/1709.09843)

