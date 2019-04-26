---
layout: post
title: "Blurring the Line Between Structure and Learning to Optimize and Adapt Receptive Fields"
date: 2019-04-25 17:57:10
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Inference
author: Evan Shelhamer, Dequan Wang, Trevor Darrell
mathjax: true
---

* content
{:toc}

##### Abstract
The visual world is vast and varied, but its variations divide into structured and unstructured factors. We compose free-form filters and structured Gaussian filters, optimized end-to-end, to factorize deep representations and learn both local features and their degree of locality. Our semi-structured composition is strictly more expressive than free-form filtering, and changes in its structured parameters would require changes in free-form architecture. In effect this optimizes over receptive field size and shape, tuning locality to the data and task. Dynamic inference, in which the Gaussian structure varies with the input, adapts receptive field size to compensate for local scale variation. Optimizing receptive field size improves semantic segmentation accuracy on Cityscapes by 1-2 points for strong dilated and skip architectures and by up to 10 points for suboptimal designs. Adapting receptive fields by dynamic Gaussian structure further improves results, equaling the accuracy of free-form deformation while improving efficiency.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.11487](http://arxiv.org/abs/1904.11487)

##### PDF
[http://arxiv.org/pdf/1904.11487](http://arxiv.org/pdf/1904.11487)

