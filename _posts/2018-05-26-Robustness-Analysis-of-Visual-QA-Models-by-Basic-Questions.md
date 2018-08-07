---
layout: post
title: "Robustness Analysis of Visual QA Models by Basic Questions"
date: 2018-05-26 05:14:02
categories: arXiv_CV
tags: arXiv_CV QA Optimization VQA
author: Jia-Hong Huang, Cuong Duc Dao, Modar Alfadly, C. Huck Yang, Bernard Ghanem
mathjax: true
---

* content
{:toc}

##### Abstract
Visual Question Answering (VQA) models should have both high robustness and accuracy. Unfortunately, most of the current VQA research only focuses on accuracy because there is a lack of proper methods to measure the robustness of VQA models. There are two main modules in our algorithm. Given a natural language question about an image, the first module takes the question as input and then outputs the ranked basic questions, with similarity scores, of the main given question. The second module takes the main question, image and these basic questions as input and then outputs the text-based answer of the main question about the given image. We claim that a robust VQA model is one, whose performance is not changed much when related basic questions as also made available to it as input. We formulate the basic questions generation problem as a LASSO optimization, and also propose a large scale Basic Question Dataset (BQD) and Rscore (novel robustness measure), for analyzing the robustness of VQA models. We hope our BQD will be used as a benchmark for to evaluate the robustness of VQA models, so as to help the community build more robust and accurate VQA models.

##### Abstract (translated by Google)
视觉问答（VQA）模型应具有高稳健性和准确性。不幸的是，目前大多数VQA研究只关注准确性，因为缺乏适当的方法来衡量VQA模型的稳健性。我们的算法有两个主要模块。给定关于图像的自然语言问题，第一模块将问题作为输入，然后输出主要给定问题的排序基本问题，具有相似性得分。第二个模块将主要问题，图像和这些基本问题作为输入，然后输出关于给定图像的主要问题的基于文本的答案。我们声称一个强大的VQA模型是一个，当相关的基本问题也可以作为输入时，其性能没有太大变化。我们将基本问题生成问题表示为LASSO优化，并提出了大规模基本问题数据集（BQD）和Rscore（新颖鲁棒性度量），用于分析VQA模型的鲁棒性。我们希望我们的BQD将用作评估VQA模型稳健性的基准，以帮助社区构建更健壮，更准确的VQA模型。

##### URL
[https://arxiv.org/abs/1709.04625](https://arxiv.org/abs/1709.04625)

##### PDF
[https://arxiv.org/pdf/1709.04625](https://arxiv.org/pdf/1709.04625)

