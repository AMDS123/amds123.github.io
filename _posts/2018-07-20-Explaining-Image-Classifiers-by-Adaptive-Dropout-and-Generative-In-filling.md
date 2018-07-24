---
layout: post
title: "Explaining Image Classifiers by Adaptive Dropout and Generative In-filling"
date: 2018-07-20 20:48:44
categories: arXiv_CV
tags: arXiv_CV Salient Image_Classification Classification
author: Chun-Hao Chang, Elliot Creager, Anna Goldenberg, David Duvenaud
mathjax: true
---

* content
{:toc}

##### Abstract
Explanations of black-box classifiers often rely on saliency maps, which score the relevance of each input dimension to the resulting classification. Recent approaches compute saliency by optimizing regions of the input that maximally change the classification outcome when replaced by a \emph{reference value}. These reference values are based on \emph{ad-hoc} heuristics such as the input mean. In this work we \emph{marginalize out} masked regions of the input, conditioning a generative model on the rest of the image. Our model-agnostic method produces realistic explanations, generating plausible inputs that would have caused the model to classify differently. When applied to image classification, our method produces more compact and relevant explanations, with fewer artifacts compared to previous methods.

##### Abstract (translated by Google)
黑盒分类器的解释通常依赖于显着性图，该显着性图对每个输入维度与所得分类的相关性进行评分。最近的方法通过优化输入的区域来计算显着性，该区域在被\ emph {参考值}替换时最大地改变分类结果。这些参考值基于\ emph {ad-hoc}启发式算法，例如输入均值。在这项工作中，我们强调{边缘化}输入的掩蔽区域，调整图像其余部分的生成模型。我们的模型不可知方法产生了真实的解释，产生了合理的输入，这些输入会导致模型的分类不同。当应用于图像分类时，我们的方法产生更紧凑和相关的解释，与先前的方法相比具有更少的伪像。

##### URL
[http://arxiv.org/abs/1807.08024](http://arxiv.org/abs/1807.08024)

##### PDF
[http://arxiv.org/pdf/1807.08024](http://arxiv.org/pdf/1807.08024)

