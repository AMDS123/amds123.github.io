---
layout: post
title: "Subject2Vec: Generative-Discriminative Approach from a Set of Image Patches to a Vector"
date: 2018-06-28 22:12:56
categories: arXiv_CV
tags: arXiv_CV Attention Deep_Learning Prediction
author: Sumedha Singla, Mingming Gong, Siamak Ravanbakhsh, Frank Sciurba, Barnabas Poczos, Kayhan N. Batmanghelich
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an attention-based method that aggregates local image features to a subject-level representation for predicting disease severity. In contrast to classical deep learning that requires a fixed dimensional input, our method operates on a set of image patches; hence it can accommodate variable length input image without image resizing. The model learns a clinically interpretable subject-level representation that is reflective of the disease severity. Our model consists of three mutually dependent modules which regulate each other: (1) a discriminative network that learns a fixed-length representation from local features and maps them to disease severity; (2) an attention mechanism that provides interpretability by focusing on the areas of the anatomy that contribute the most to the prediction task; and (3) a generative network that encourages the diversity of the local latent features. The generative term ensures that the attention weights are non-degenerate while maintaining the relevance of the local regions to the disease severity. We train our model end-to-end in the context of a large-scale lung CT study of Chronic Obstructive Pulmonary Disease (COPD). Our model gives state-of-the art performance in predicting clinical measures of severity for COPD. The distribution of the attention provides the regional relevance of lung tissue to the clinical measurements.

##### Abstract (translated by Google)
我们提出了一种基于注意力的方法，可将局部图像特征聚合到用于预测疾病严重程度的主体级别表示中。与需要固定尺寸输入的传统深度学习相比，我们的方法在一组图像补丁上运行;因此它可以容纳可变长度的输入图像而不用调整图像大小。该模型学习可反映疾病严重程度的临床可解释的科目水平表示。我们的模型由三个相互依赖的模块组成，它们相互调节：（1）一个区分网络，从局部特征中学习一个固定长度的表示，并将它们映射到疾病的严重程度; （2）注意机制，通过关注对预测任务贡献最大的解剖结构的区域来提供可解释性; （3）鼓励当地潜在特征多样性的生成网络。生成术语确保注意力权重不退化，同时保持局部区域与疾病严重程度的相关性。我们在慢性阻塞性肺疾病（COPD）的大规模肺部CT研究的背景下端对端地训练我们的模型。我们的模型在预测慢性阻塞性肺病严重程度的临床措施方面提供了最先进的表现。注意的分布提供了肺组织对临床测量的区域相关性。

##### URL
[http://arxiv.org/abs/1806.11217](http://arxiv.org/abs/1806.11217)

##### PDF
[http://arxiv.org/pdf/1806.11217](http://arxiv.org/pdf/1806.11217)

