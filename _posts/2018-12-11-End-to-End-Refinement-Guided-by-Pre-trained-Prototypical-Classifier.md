---
layout: post
title: "End-to-End Refinement Guided by Pre-trained Prototypical Classifier"
date: 2018-12-11 16:51:58
categories: arXiv_AI
tags: arXiv_AI Knowledge Embedding Quantitative
author: Junwen Bai, Zihang Lai, Runzhe Yang, Yexiang Xue, John Gregoire, Carla Gomes
mathjax: true
---

* content
{:toc}

##### Abstract
Many real-world tasks involve identifying patterns from data satisfying background or prior knowledge. In domains like materials discovery, due to the flaws and biases in raw experimental data, the identification of X-ray diffraction patterns (XRD) often requires a huge amount of manual work in finding refined phases that are similar to the ideal theoretical ones. Automatically refining the raw XRDs utilizing the simulated theoretical data is thus desirable. We propose imitation refinement, a novel approach to refine imperfect input patterns, guided by a pre-trained classifier incorporating prior knowledge from simulated theoretical data, such that the refined patterns imitate the ideal data. The classifier is trained on the ideal simulated data to classify patterns and learns an embedding space where each class is represented by a prototype. The refiner learns to refine the imperfect patterns with small modifications, such that their embeddings are closer to the corresponding prototypes. We show that the refiner can be trained in both supervised and unsupervised fashions. We further illustrate the effectiveness of the proposed approach both qualitatively and quantitatively in a digit refinement task and an X-ray diffraction pattern refinement task in materials discovery.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.08698](http://arxiv.org/abs/1805.08698)

##### PDF
[http://arxiv.org/pdf/1805.08698](http://arxiv.org/pdf/1805.08698)

