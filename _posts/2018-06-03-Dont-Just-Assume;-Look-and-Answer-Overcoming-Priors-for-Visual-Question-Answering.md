---
layout: post
title: "Don't Just Assume; Look and Answer: Overcoming Priors for Visual Question Answering"
date: 2018-06-03 15:32:06
categories: arXiv_CV
tags: arXiv_CV QA Attention Relation VQA Recognition
author: Aishwarya Agrawal, Dhruv Batra, Devi Parikh, Aniruddha Kembhavi
mathjax: true
---

* content
{:toc}

##### Abstract
A number of studies have found that today's Visual Question Answering (VQA) models are heavily driven by superficial correlations in the training data and lack sufficient image grounding. To encourage development of models geared towards the latter, we propose a new setting for VQA where for every question type, train and test sets have different prior distributions of answers. Specifically, we present new splits of the VQA v1 and VQA v2 datasets, which we call Visual Question Answering under Changing Priors (VQA-CP v1 and VQA-CP v2 respectively). First, we evaluate several existing VQA models under this new setting and show that their performance degrades significantly compared to the original VQA setting. Second, we propose a novel Grounded Visual Question Answering model (GVQA) that contains inductive biases and restrictions in the architecture specifically designed to prevent the model from 'cheating' by primarily relying on priors in the training data. Specifically, GVQA explicitly disentangles the recognition of visual concepts present in the image from the identification of plausible answer space for a given question, enabling the model to more robustly generalize across different distributions of answers. GVQA is built off an existing VQA model -- Stacked Attention Networks (SAN). Our experiments demonstrate that GVQA significantly outperforms SAN on both VQA-CP v1 and VQA-CP v2 datasets. Interestingly, it also outperforms more powerful VQA models such as Multimodal Compact Bilinear Pooling (MCB) in several cases. GVQA offers strengths complementary to SAN when trained and evaluated on the original VQA v1 and VQA v2 datasets. Finally, GVQA is more transparent and interpretable than existing VQA models.

##### Abstract (translated by Google)
许多研究发现，今天的视觉问答（VQA）模型很大程度上是由训练数据中的表面相关性驱动的，缺乏足够的图像基础。为了鼓励开发面向后者的模型，我们为VQA提出了一个新的设置，其中每个问题类型，训练和测试集都有不同的先前答案分布。具体来说，我们提出了VQA v1和VQA v2数据集的新分割，我们称之为Change Priors下的Visual Question Answering（分别为VQA-CP v1和VQA-CP v2）。首先，我们在此新设置下评估了几个现有的VQA模型，并显示与原始VQA设置相比，它们的性能显着下降。其次，我们提出了一种新颖的基础视觉问题回答模型（GVQA），该模型包含体系结构中的归纳偏差和限制，专门用于防止模型主要依赖于训练数据中的先验而“欺骗”。具体而言，GVQA明确地解除了对图像中存在的视觉概念的识别，从识别给定问题的似是而非的答案空间，使得模型能够更加稳健地概括不同的答案分布。 GVQA基于现有的VQA模型 -  Stacked Attention Networks（SAN）。我们的实验表明，在VQA-CP v1和VQA-CP v2数据集上，GVQA明显优于SAN。有趣的是，它在某些情况下也优于更强大的VQA模型，例如Multimodal Compact Bilinear Pooling（MCB）。在原始VQA v1和VQA v2数据集上进行培训和评估时，GVQA提供与SAN互补的优势。最后，GVQA比现有的VQA模型更加透明和可解释。

##### URL
[https://arxiv.org/abs/1712.00377](https://arxiv.org/abs/1712.00377)

##### PDF
[https://arxiv.org/pdf/1712.00377](https://arxiv.org/pdf/1712.00377)

