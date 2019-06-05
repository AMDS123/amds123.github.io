---
layout: post
title: "Evaluating Scalable Bayesian Deep Learning Methods for Robust Computer Vision"
date: 2019-06-04 17:54:20
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Deep_Learning Prediction
author: Fredrik K. Gustafsson, Martin Danelljan, Thomas B. Sch&#xf6;n
mathjax: true
---

* content
{:toc}

##### Abstract
While Deep Neural Networks (DNNs) have become the go-to approach in computer vision, the vast majority of these models fail to properly capture the uncertainty inherent in their predictions. Estimating this predictive uncertainty can be crucial, for instance in automotive applications. In Bayesian deep learning, predictive uncertainty is often decomposed into the distinct types of aleatoric and epistemic uncertainty. The former can be estimated by letting a DNN output the parameters of a probability distribution. Epistemic uncertainty estimation is a more challenging problem, and while different scalable methods recently have emerged, no comprehensive comparison has been performed in a real-world setting. We therefore accept this task and propose an evaluation framework for predictive uncertainty estimation that is specifically designed to test the robustness required in real-world computer vision applications. Using the proposed framework, we perform an extensive comparison of the popular ensembling and MC-dropout methods on the tasks of depth completion and street-scene semantic segmentation. Our comparison suggests that ensembling consistently provides more reliable uncertainty estimates. Code is available at https://github.com/fregu856/evaluating_bdl.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.01620](http://arxiv.org/abs/1906.01620)

##### PDF
[http://arxiv.org/pdf/1906.01620](http://arxiv.org/pdf/1906.01620)

