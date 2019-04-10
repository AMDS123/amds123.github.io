---
layout: post
title: "Uncertainty Measures and Prediction Quality Rating for the Semantic Segmentation of Nested Multi Resolution Street Scene Images"
date: 2019-04-09 08:14:09
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Classification Prediction
author: Matthias Rottmann, Marius Schubert
mathjax: true
---

* content
{:toc}

##### Abstract
In the semantic segmentation of street scenes the reliability of the prediction and therefore uncertainty measures are of highest interest. We present a method that generates for each input image a hierarchy of nested crops around the image center and presents these, all re-scaled to the same size, to a neural network for semantic segmentation. The resulting softmax outputs are then post processed such that we can investigate mean and variance over all image crops as well as mean and variance of uncertainty heat maps obtained from pixel-wise uncertainty measures, like the entropy, applied to each crop's softmax output. In our tests, we use the publicly available DeepLabv3+ MobilenetV2 network (trained on the Cityscapes dataset) and demonstrate that the incorporation of crops improves the quality of the prediction and that we obtain more reliable uncertainty measures. These are then aggregated over predicted segments for either classifying between IoU=0 and IoU&gt;0 (meta classification) or predicting the IoU via linear regression (meta regression). The latter yields reliable performance estimates for segmentation networks, in particular useful in the absence of ground truth. For the task of meta classification we obtain a classification accuracy of $81.93\%$ and an AUROC of $89.89\%$. For meta regression we obtain an $R^2$ value of $84.77\%$. These results yield significant improvements compared to other approaches.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.04516](http://arxiv.org/abs/1904.04516)

##### PDF
[http://arxiv.org/pdf/1904.04516](http://arxiv.org/pdf/1904.04516)

