---
layout: post
title: "GAN Dissection: Visualizing and Understanding Generative Adversarial Networks"
date: 2018-11-26 18:59:07
categories: arXiv_AI
tags: arXiv_AI Adversarial Segmentation GAN Relation
author: David Bau, Jun-Yan Zhu, Hendrik Strobelt, Bolei Zhou, Joshua B. Tenenbaum, William T. Freeman, Antonio Torralba
mathjax: true
---

* content
{:toc}

##### Abstract
Generative Adversarial Networks (GANs) have recently achieved impressive results for many real-world applications, and many GAN variants have emerged with improvements in sample quality and training stability. However, visualization and understanding of GANs is largely missing. How does a GAN represent our visual world internally? What causes the artifacts in GAN results? How do architectural choices affect GAN learning? Answering such questions could enable us to develop new insights and better models. In this work, we present an analytic framework to visualize and understand GANs at the unit-, object-, and scene-level. We first identify a group of interpretable units that are closely related to object concepts with a segmentation-based network dissection method. Then, we quantify the causal effect of interpretable units by measuring the ability of interventions to control objects in the output. Finally, we examine the contextual relationship between these units and their surrounding by inserting the discovered object concepts into new images. We show several practical applications enabled by our framework, from comparing internal representations across different layers, models, and datasets, to improving GANs by locating and removing artifact-causing units, to interactively manipulating objects in the scene. We provide open source interpretation tools to help peer researchers and practitioners better understand their GAN models.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1811.10597](https://arxiv.org/abs/1811.10597)

##### PDF
[https://arxiv.org/pdf/1811.10597](https://arxiv.org/pdf/1811.10597)

