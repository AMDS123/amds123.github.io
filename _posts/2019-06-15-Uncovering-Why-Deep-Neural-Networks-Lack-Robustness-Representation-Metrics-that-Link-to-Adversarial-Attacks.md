---
layout: post
title: "Uncovering Why Deep Neural Networks Lack Robustness: Representation Metrics that Link to Adversarial Attacks"
date: 2019-06-15 23:32:33
categories: arXiv_CV
tags: arXiv_CV Adversarial Classification
author: Danilo Vasconcellos Vargas, Shashank Kotyan, Moe Matsuki
mathjax: true
---

* content
{:toc}

##### Abstract
Neural networks have been shown vulnerable to adversarial samples. Slightly perturbed input images are able to change the classification of accurate models, showing that the representation learned is not as good as previously thought.To aid the development of better neural networks, it would be important to evaluate to what extent are current neural networks' representations capturing the existing features.Here we propose a test that can evaluate neural networks using a new type of zero-shot test, entitled Raw Zero-Shot.This test is based on the principle that some features are present on unknown classes and that unknown classes can be defined as a combination of previous learned features without learning bias. To evaluate the soft-labels of unknown classes, two metrics are proposed.One is based on clustering validation techniques (Davies-Bouldin Index) and the other is based on soft-label distance of a given correct soft-label.Experiments show that such metrics are in accordance with the robustness to adversarial attacks and might serve as a guidance to build better models as well as be used in loss functions to improve the models directly.Interestingly, the results suggests that dynamic routing networks such as CapsNet have better representation while some DNNs might be trading off representation quality for accuracy. 
 Code available at \url{<a href="http://bit.ly/RepresentationMetrics">this http URL</a>}.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.06627](http://arxiv.org/abs/1906.06627)

##### PDF
[http://arxiv.org/pdf/1906.06627](http://arxiv.org/pdf/1906.06627)

