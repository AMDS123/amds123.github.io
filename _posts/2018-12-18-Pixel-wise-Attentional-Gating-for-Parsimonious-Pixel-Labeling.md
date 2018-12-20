---
layout: post
title: "Pixel-wise Attentional Gating for Parsimonious Pixel Labeling"
date: 2018-12-18 22:46:32
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention Face CNN Semantic_Segmentation Inference Detection
author: Shu Kong, Charless Fowlkes
mathjax: true
---

* content
{:toc}

##### Abstract
To achieve parsimonious inference in per-pixel labeling tasks with a limited computational budget, we propose a \emph{Pixel-wise Attentional Gating} unit (\emph{PAG}) that learns to selectively process a subset of spatial locations at each layer of a deep convolutional network. PAG is a generic, architecture-independent, problem-agnostic mechanism that can be readily "plugged in" to an existing model with fine-tuning. We utilize PAG in two ways: 1) learning spatially varying pooling fields that improve model performance without the extra computation cost associated with multi-scale pooling, and 2) learning a dynamic computation policy for each pixel to decrease total computation while maintaining accuracy. 
 We extensively evaluate PAG on a variety of per-pixel labeling tasks, including semantic segmentation, boundary detection, monocular depth and surface normal estimation. We demonstrate that PAG allows competitive or state-of-the-art performance on these tasks. Our experiments show that PAG learns dynamic spatial allocation of computation over the input image which provides better performance trade-offs compared to related approaches (e.g., truncating deep models or dynamically skipping whole layers). Generally, we observe PAG can reduce computation by $10\%$ without noticeable loss in accuracy and performance degrades gracefully when imposing stronger computational constraints.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.01556](http://arxiv.org/abs/1805.01556)

##### PDF
[http://arxiv.org/pdf/1805.01556](http://arxiv.org/pdf/1805.01556)

