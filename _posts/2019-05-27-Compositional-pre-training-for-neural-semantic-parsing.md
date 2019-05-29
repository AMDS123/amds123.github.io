---
layout: post
title: "Compositional pre-training for neural semantic parsing"
date: 2019-05-27 22:51:39
categories: arXiv_CL
tags: arXiv_CL Knowledge Inference
author: Amir Ziai
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic parsing is the process of translating natural language utterances into logical forms, which has many important applications such as question answering and instruction following. Sequence-to-sequence models have been very successful across many NLP tasks. However, a lack of task-specific prior knowledge can be detrimental to the performance of these models. Prior work has used frameworks for inducing grammars over the training examples, which capture conditional independence properties that the model can leverage. Inspired by the recent success stories such as BERT we set out to extend this augmentation framework into two stages. The first stage is to pre-train using a corpus of augmented examples in an unsupervised manner. The second stage is to fine-tune to a domain-specific task. In addition, since the pre-training stage is separate from the training on the main task we also expand the universe of possible augmentations without causing catastrophic inference. We also propose a novel data augmentation strategy that interchanges tokens that co-occur in similar contexts to produce new training pairs. We demonstrate that the proposed two-stage framework is beneficial for improving the parsing accuracy in a standard dataset called GeoQuery for the task of generating logical forms from a set of questions about the US geography.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.11531](https://arxiv.org/abs/1905.11531)

##### PDF
[https://arxiv.org/pdf/1905.11531](https://arxiv.org/pdf/1905.11531)

