---
layout: post
title: "Don't Just Assume; Look and Answer: Overcoming Priors for Visual Question Answering"
date: 2017-12-01 15:48:50
categories: arXiv_CV
tags: arXiv_CV VQA Recognition
author: Aishwarya Agrawal, Dhruv Batra, Devi Parikh, Aniruddha Kembhavi
mathjax: true
---

* content
{:toc}

##### Abstract
A number of studies have found that today's Visual Question Answering (VQA) models are heavily driven by superficial correlations in the training data and lack sufficient image grounding. To encourage development of models geared towards the latter, we propose a new setting for VQA where for every question type, train and test sets have different prior distributions of answers. Specifically, we present new splits of the VQA v1 and VQA v2 datasets, which we call Visual Question Answering under Changing Priors (VQA-CP v1 and VQA-CP v2 respectively). First, we evaluate several existing VQA models under this new setting and show that their performance degrades significantly compared to the original VQA setting. Second, we propose a novel Grounded Visual Question Answering model (GVQA) that contains inductive biases and restrictions in the architecture specifically designed to prevent the model from 'cheating' by primarily relying on priors in the training data. Specifically, GVQA explicitly disentangles the recognition of visual concepts present in the image from the identification of plausible answer space for a given question, enabling the model to more robustly generalize across different distributions of answers. GVQA is built off an existing VQA model -- Stacked Attention Networks (SAN). Our experiments demonstrate that GVQA significantly outperforms SAN on both VQA-CP v1 and VQA-CP v2 datasets. Interestingly, it also outperforms more powerful VQA models such as Multimodal Compact Bilinear Pooling (MCB) in several cases. GVQA offers strengths complementary to SAN when trained and evaluated on the original VQA v1 and VQA v2 datasets. Finally, GVQA is more transparent and interpretable than existing VQA models.

##### Abstract (translated by Google)
许多研究发现，今天的视觉问题回答（VQA）模型主要是由训练数据中的表面相关性驱动，缺乏足够的图像基础。为了鼓励开发面向后者的模型，我们提出了一个VQA的新的设置，对于每个问题类型，列车和测试集具有不同的先前分布的答案。具体而言，我们提出了VQA v1和VQA v2数据集的新分割，我们将其称为VQA-CP v1和VQA-CP v2下的Visual Question Answering。首先，我们评估几个现有的VQA模型在这个新的设置下，并且显示它们的性能相比于原始的VQA设置明显降低。其次，我们提出了一种新颖的基于视觉问答的模型（GVQA），其中包含了专门设计用来防止模型主要依靠训练数据中的先验“欺骗”的体系结构中的归纳偏见和限制。具体来说，GVQA明确地解释了从给定问题的合理答案空间的识别中识别图像中存在的视觉概念，使得模型能够在不同分布的答案中更强有力地推广。 GVQA是建立在现有的VQA模型 - 堆叠式关注网络（SAN）之上的。我们的实验证明，在VQA-CP v1和VQA-CP v2数据集上，GVQA显着优于SAN。有趣的是，它也胜过了更强大的VQA模型，如多模式紧凑双线性池（MCB）。 GVQA在对原始VQA v1和VQA v2数据集进行培训和评估时，提供了与SAN相辅相成的优势。最后，GVQA比现有的VQA模型更加透明和可解释。

##### URL
[https://arxiv.org/abs/1712.00377](https://arxiv.org/abs/1712.00377)

##### PDF
[https://arxiv.org/pdf/1712.00377](https://arxiv.org/pdf/1712.00377)

