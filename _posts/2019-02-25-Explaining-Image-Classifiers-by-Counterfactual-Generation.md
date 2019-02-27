---
layout: post
title: "Explaining Image Classifiers by Counterfactual Generation"
date: 2019-02-25 16:22:07
categories: arXiv_CV
tags: arXiv_CV Salient Prediction Relation
author: Chun-Hao Chang, Elliot Creager, Anna Goldenberg, David Duvenaud
mathjax: true
---

* content
{:toc}

##### Abstract
When an image classifier makes a prediction, which parts of the image are relevant and why? We can rephrase this question to ask: which parts of the image, if they were not seen by the classifier, would most change its decision? Producing an answer requires marginalizing over images that could have been seen but weren't. We can sample plausible image in-fills by conditioning a generative model on the rest of the image. We then optimize to find the image regions that most change the classifier's decision after in-fill. Our approach contrasts with ad-hoc in-filling approaches, such as blurring or injecting noise, which generate inputs far from the data distribution, and ignore informative relationships between different parts of the image. Our method produces more compact and relevant saliency maps, with fewer artifacts compared to previous methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1807.08024](http://arxiv.org/abs/1807.08024)

##### PDF
[http://arxiv.org/pdf/1807.08024](http://arxiv.org/pdf/1807.08024)

