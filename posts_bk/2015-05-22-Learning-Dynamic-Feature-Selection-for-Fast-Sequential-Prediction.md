---
layout: post
title: "Learning Dynamic Feature Selection for Fast Sequential Prediction"
date: 2015-05-22 18:28:21
categories: arXiv_CL
tags: arXiv_CL Inference Prediction Recognition
author: Emma Strubell, Luke Vilnis, Kate Silverstein, Andrew McCallum
mathjax: true
---

* content
{:toc}

##### Abstract
We present paired learning and inference algorithms for significantly reducing computation and increasing speed of the vector dot products in the classifiers that are at the heart of many NLP components. This is accomplished by partitioning the features into a sequence of templates which are ordered such that high confidence can often be reached using only a small fraction of all features. Parameter estimation is arranged to maximize accuracy and early confidence in this sequence. Our approach is simpler and better suited to NLP than other related cascade methods. We present experiments in left-to-right part-of-speech tagging, named entity recognition, and transition-based dependency parsing. On the typical benchmarking datasets we can preserve POS tagging accuracy above 97% and parsing LAS above 88.5% both with over a five-fold reduction in run-time, and NER F1 above 88 with more than 2x increase in speed.

##### Abstract (translated by Google)
我们提出了成对的学习和推理算法，以显着减少计算量，并提高分类器中矢量点产品的速度，分类器是许多NLP组件的核心。这是通过将特征划分成一系列模板来完成的，这些模板是有序的，使得通常仅使用所有特征的一小部分就可以达到高置信度。参数估计被安排为使该序列中的准确性和早期置信度最大化。我们的方法比其他相关的级联方法更简单，更适合于NLP。我们提出了从左到右的词性标注，命名实体识别和基于转换的依赖分析的实验。在典型的基准测试数据集上，我们可以将POS标记精度保持在97％以上，解析LAS超过88.5％，运行时间减少5倍以上，NER F1高于88，速度提高2倍以上。

##### URL
[https://arxiv.org/abs/1505.06169](https://arxiv.org/abs/1505.06169)

##### PDF
[https://arxiv.org/pdf/1505.06169](https://arxiv.org/pdf/1505.06169)

