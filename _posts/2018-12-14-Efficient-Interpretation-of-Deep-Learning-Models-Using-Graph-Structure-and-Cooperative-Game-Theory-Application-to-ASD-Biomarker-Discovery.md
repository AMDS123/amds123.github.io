---
layout: post
title: "Efficient Interpretation of Deep Learning Models Using Graph Structure and Cooperative Game Theory: Application to ASD Biomarker Discovery"
date: 2018-12-14 21:50:02
categories: arXiv_CV
tags: arXiv_CV Deep_Learning Prediction
author: Xiaoxiao Li, Nicha C. Dvornek, Yuan Zhou, Juntang Zhuang, Pamela Ventola, James S. Duncan
mathjax: true
---

* content
{:toc}

##### Abstract
Discovering imaging biomarkers for autism spectrum disorder (ASD) is critical to help explain ASD and predict or monitor treatment outcomes. Toward this end, deep learning classifiers have recently been used for identifying ASD from functional magnetic resonance imaging (fMRI) with higher accuracy than traditional learning strategies. However, a key challenge with deep learning models is understanding just what image features the network is using, which can in turn be used to define the biomarkers. Current methods extract biomarkers, i.e., important features, by looking at how the prediction changes if "ignoring" one feature at a time. In this work, we go beyond looking at only individual features by using Shapley value explanation (SVE) from cooperative game theory. Cooperative game theory is advantageous here because it directly considers the interaction between features and can be applied to any machine learning method, making it a novel, more accurate way of determining instance-wise biomarker importance from deep learning models. A barrier to using SVE is its computational complexity: $2^N$ given $N$ features. We explicitly reduce the complexity of SVE computation by two approaches based on the underlying graph structure of the input data: 1) only consider the centralized coalition of each feature; 2) a hierarchical pipeline which first clusters features into small communities, then applies SVE in each community. Monte Carlo approximation can be used for large permutation sets. We first validate our methods on the MNIST dataset and compare to human perception. Next, to insure plausibility of our biomarker results, we train a Random Forest (RF) to classify ASD/control subjects from fMRI and compare SVE results to standard RF-based feature importance. Finally, we show initial results on ranked fMRI biomarkers using SVE on a deep learning classifier for the ASD/control dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.06181](http://arxiv.org/abs/1812.06181)

##### PDF
[http://arxiv.org/pdf/1812.06181](http://arxiv.org/pdf/1812.06181)

