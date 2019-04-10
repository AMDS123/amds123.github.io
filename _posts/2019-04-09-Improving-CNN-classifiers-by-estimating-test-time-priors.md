---
layout: post
title: "Improving CNN classifiers by estimating test-time priors"
date: 2019-04-09 08:36:53
categories: arXiv_CV
tags: arXiv_CV Classification Prediction
author: Milan Sulc, Jiri Matas
mathjax: true
---

* content
{:toc}

##### Abstract
The problem of different training and test set class priors is addressed in the context of CNN classifiers. We compare two different approaches to estimating the new priors: an existing Maximum Likelihood Estimation approach (optimized by an EM algorithm or by projected gradient descend) and a proposed Maximum a Posteriori approach, which increases the stability of the estimate by introducing a Dirichlet hyper-prior on the class prior probabilities. Experimental results show a significant improvement on the fine-grained classification tasks using known evaluation-time priors, increasing the top-1 accuracy by 4.0% on the FGVC iNaturalist 2018 validation set and by 3.9% on the FGVCx Fungi 2018 validation set. Estimation of the unknown test set priors noticeably increases the accuracy on the PlantCLEF dataset, allowing a single CNN model to achieve state-of-the-art results and outperform the competition-winning ensemble of 12 CNNs. The proposed Maximum a Posteriori estimation increases the prediction accuracy by 2.8% on PlantCLEF 2017 and by 1.8% on FGVCx Fungi, where the existing MLE method would lead to a decrease accuracy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.08235](http://arxiv.org/abs/1805.08235)

##### PDF
[http://arxiv.org/pdf/1805.08235](http://arxiv.org/pdf/1805.08235)

