---
layout: post
title: "Pixel-wise Attentional Gating for Parsimonious Pixel Labeling"
date: 2018-05-03 22:05:57
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
为了在有限计算预算的每像素标记任务中实现简洁推理，我们提出了一种\ emph {逐像素注意门控}单元（\ emph {PAG}），该单元学习选择性地处理每层的空间位置子集一个深度卷积网络。 PAG是一种通用的，架构无关的，问题不可知的机制，可以通过微调轻松“插入”现有模型。我们以两种方式利用PAG：1）学习空间变化的池场，以提高模型性能，而不需要与多尺度池相关的额外计算成本; 2）学习每个像素的动态计算策略，以减少总计算量，同时保持准确性。
 我们广泛评估PAG的各种像素标记任务，包括语义分割，边界检测，单目深度和表面法线估计。我们证明PAG可以为这些任务提供具有竞争力或最先进的性能。我们的实验表明，PAG学习输入图像上的计算的动态空间分配，与相关方法（例如，截断深层模型或动态跳过整个层）相比，提供了更好的性能折衷。一般来说，我们观察到，PAG可以减少10美元/美元的计算量，而且在施加更强的计算约束时，精度和性能会显着降低。

##### URL
[http://arxiv.org/abs/1805.01556](http://arxiv.org/abs/1805.01556)

##### PDF
[http://arxiv.org/pdf/1805.01556](http://arxiv.org/pdf/1805.01556)

