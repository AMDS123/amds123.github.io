---
layout: post
title: "Application of Decision Rules for Handling Class Imbalance in Semantic Segmentation"
date: 2019-01-24 13:20:25
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Classification Detection
author: Robin Chan, Matthias Rottmann, Fabian H&#xfc;ger, Peter Schlicht, Hanno Gottschalk
mathjax: true
---

* content
{:toc}

##### Abstract
As part of autonomous car driving systems, semantic segmentation is an essential component to obtain a full understanding of the car's environment. One difficulty, that occurs while training neural networks for this purpose, is class imbalance of training data. Consequently, a neural network trained on unbalanced data in combination with maximum a-posteriori classification may easily ignore classes that are rare in terms of their frequency in the dataset. However, these classes are often of highest interest. We approach such potential misclassifications by weighting the posterior class probabilities with the prior class probabilities which in our case are the inverse frequencies of the corresponding classes in the training dataset. More precisely, we adopt a localized method by computing the priors pixel-wise such that the impact can be analyzed at pixel level as well. In our experiments, we train one network from scratch using a proprietary dataset containing 20,000 annotated frames of video sequences recorded from street scenes. The evaluation on our test set shows an increase of average recall with regard to instances of pedestrians and info signs by $25\%$ and $23.4\%$, respectively. In addition, we significantly reduce the non-detection rate for instances of the same classes by $61\%$ and $38\%$.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.08394](http://arxiv.org/abs/1901.08394)

##### PDF
[http://arxiv.org/pdf/1901.08394](http://arxiv.org/pdf/1901.08394)

