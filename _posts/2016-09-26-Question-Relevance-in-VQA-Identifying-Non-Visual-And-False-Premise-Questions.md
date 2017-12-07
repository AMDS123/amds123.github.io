---
layout: post
title: "Question Relevance in VQA: Identifying Non-Visual And False-Premise Questions"
date: 2016-09-26 15:24:28
categories: arXiv_CV
tags: arXiv_CV QA Caption RNN VQA
author: Arijit Ray, Gordon Christie, Mohit Bansal, Dhruv Batra, Devi Parikh
mathjax: true
---

* content
{:toc}

##### Abstract
Visual Question Answering (VQA) is the task of answering natural-language questions about images. We introduce the novel problem of determining the relevance of questions to images in VQA. Current VQA models do not reason about whether a question is even related to the given image (e.g. What is the capital of Argentina?) or if it requires information from external resources to answer correctly. This can break the continuity of a dialogue in human-machine interaction. Our approaches for determining relevance are composed of two stages. Given an image and a question, (1) we first determine whether the question is visual or not, (2) if visual, we determine whether the question is relevant to the given image or not. Our approaches, based on LSTM-RNNs, VQA model uncertainty, and caption-question similarity, are able to outperform strong baselines on both relevance tasks. We also present human studies showing that VQA models augmented with such question relevance reasoning are perceived as more intelligent, reasonable, and human-like.

##### Abstract (translated by Google)
视觉问答（VQA）是回答关于图像的自然语言问题的任务。我们介绍了确定问题与VQA中图像相关性的新问题。目前的VQA模型并不能推断问题是否与给定的图像有关（例如，什么是阿根廷的首都？），还是需要来自外部资源的信息才能正确回答。这可能会打破人机对话的连续性。我们确定相关性的方法由两个阶段组成。给出一个图像和一个问题，（1）我们首先确定问题是否是视觉的，（2）如果是视觉的，我们确定问题是否与给定的图像有关。我们基于LSTM-RNN，VQA模型不确定性和字幕问题相似性的方法能够在两个相关性任务上超越强基线。我们还展示了人类研究，表明VQA模型与这种问题相关性推理增强被认为是更聪明，合理，和人类。

##### URL
[https://arxiv.org/abs/1606.06622](https://arxiv.org/abs/1606.06622)

##### PDF
[https://arxiv.org/pdf/1606.06622](https://arxiv.org/pdf/1606.06622)

