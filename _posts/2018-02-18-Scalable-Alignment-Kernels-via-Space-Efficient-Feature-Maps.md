---
layout: post
title: "Scalable Alignment Kernels via Space-Efficient Feature Maps"
date: 2018-02-18 14:16:28
categories: arXiv_AI
tags: arXiv_AI Embedding Classification Prediction
author: Yasuo Tabei, Yoshihiro Yamanishi, Rasmus Pagh
mathjax: true
---

* content
{:toc}

##### Abstract
String kernels are attractive data analysis tools for analyzing string data. Among them, alignment kernels are known for their high prediction accuracies in string classifications when tested in combination with SVMs in various applications. However, alignment kernels have a crucial drawback in that they scale poorly due to their quadratic computation complexity in the number of input strings, which limits large-scale applications in practice. We present the first approximation named ESP+SFM for alignment kernels by leveraging a metric embedding named edit-sensitive parsing (ESP) and space-efficient feature maps (SFM) for random Fourier features (RFF) for large-scale string analyses. Input strings are projected into vectors of RFF by leveraging ESP and SFM. Then, SVMs are trained on the projected vectors, which enables to significantly improve the scalability of alignment kernels while preserving their prediction accuracies. We experimentally test ESP+ SFM on its ability to learn SVMs for large-scale string classifications with various massive string data, and we demonstrate the superior performance of ESP+SFM with respect to prediction accuracy, scalability and computation efficiency.

##### Abstract (translated by Google)
字符串内核是分析字符串数据的有吸引力的数据分析工具。其中，对齐内核因其在各种应用中与支持向量机结合使用时在字符串分类中的高预测准确度而闻名。然而，对齐内核有一个关键的缺点，即由于它们在输入字符串的数量上的二次计算复杂度而导致它们缩小，这在实践中限制了大规模应用。我们通过利用称为编辑敏感解析（ESP）的度量嵌入和用于大规模字符串分析的随机傅立叶特征（RFF）的空间高效特征映射（SFM），提出了用于对齐内核的名为ESP + SFM的第一近似。通过利用ESP和SFM将输入字符串投影到RFF的向量中。然后，对投影矢量进行SVM训练，这可以显着提高对齐内核的可伸缩性，同时保持其预测精度。我们通过实验测试了ESP + SFM在学习支持各种大量字符串数据的大规模字符串分类SVM方面的能力，并证明了ESP + SFM在预测准确性，可扩展性和计算效率方面的卓越性能。

##### URL
[http://arxiv.org/abs/1802.06382](http://arxiv.org/abs/1802.06382)

##### PDF
[http://arxiv.org/pdf/1802.06382](http://arxiv.org/pdf/1802.06382)

