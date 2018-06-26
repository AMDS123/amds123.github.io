---
layout: post
title: "Extracting Tree-structures in CT data by Tracking Multiple Statistically Ranked Hypotheses"
date: 2018-06-23 15:03:09
categories: arXiv_CV
tags: arXiv_CV Segmentation Tracking
author: Raghavendra Selvan, Jens Petersen, Jesper H Pedersen, Marleen de Bruijne
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we adapt a method based on multiple hypothesis tracking (MHT) that has been shown to give state-of-the-art vessel segmentation results in interactive settings, for the purpose of extracting trees. Regularly spaced tubular templates are fit to image data forming local hypotheses. These local hypotheses are used to construct the MHT tree, which is then traversed to make segmentation decisions. However, some critical parameters in this method are scale-dependent and have an adverse effect when tracking structures of varying dimensions. We propose to use statistical ranking of local hypotheses in constructing the MHT tree, which yields a probabilistic interpretation of scores across scales and helps alleviate the scale-dependence of MHT parameters. This enables our method to track trees starting from a single seed point. Our method is evaluated on chest CT data to extract airway trees and coronary arteries. In both cases, we show that our method performs significantly better than the original MHT method.

##### Abstract (translated by Google)
在这项工作中，我们调整了一种基于多假设跟踪（MHT）的方法，该方法已被证明可以在交互设置中提供最先进的船舶分割结果，以提取树木。定期间隔的管状模板适合于形成局部假设的图像数据。这些局部假设用于构造MHT树，然后遍历该MHT树以作出分割决定。然而，这种方法中的一些关键参数与尺度有关，并且在追踪不同尺寸的结构时具有不利影响。我们建议在构建MHT树时使用局部假设的统计排序，这将产生跨尺度分数的概率解释，并有助于减轻MHT参数的尺度依赖性。这使我们的方法能够从单个种子点开始跟踪树。我们的方法在胸部CT数据上评估以提取气道树和冠状动脉。在这两种情况下，我们都表明我们的方法比原来的MHT方法表现得更好。

##### URL
[http://arxiv.org/abs/1806.08981](http://arxiv.org/abs/1806.08981)

##### PDF
[http://arxiv.org/pdf/1806.08981](http://arxiv.org/pdf/1806.08981)

