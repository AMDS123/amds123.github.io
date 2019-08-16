---
layout: post
title: "To complete or to estimate, that is the question: A Multi-Task Approach to Depth Completion and Monocular Depth Estimation"
date: 2019-08-15 13:50:50
categories: arXiv_CV
tags: arXiv_CV Adversarial Sparse
author: Amir Atapour-Abarghouei, Toby P. Breckon
mathjax: true
---

* content
{:toc}

##### Abstract
Robust three-dimensional scene understanding is now an ever-growing area of research highly relevant in many real-world applications such as autonomous driving and robotic navigation. In this paper, we propose a multi-task learning-based model capable of performing two tasks:- sparse depth completion (i.e. generating complete dense scene depth given a sparse depth image as the input) and monocular depth estimation (i.e. predicting scene depth from a single RGB image) via two sub-networks jointly trained end to end using data randomly sampled from a publicly available corpus of synthetic and real-world images. The first sub-network generates a sparse depth image by learning lower level features from the scene and the second predicts a full dense depth image of the entire scene, leading to a better geometric and contextual understanding of the scene and, as a result, superior performance of the approach. The entire model can be used to infer complete scene depth from a single RGB image or the second network can be used alone to perform depth completion given a sparse depth input. Using adversarial training, a robust objective function, a deep architecture relying on skip connections and a blend of synthetic and real-world training data, our approach is capable of producing superior high quality scene depth. Extensive experimental evaluation demonstrates the efficacy of our approach compared to contemporary state-of-the-art techniques across both problem domains.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.05540](http://arxiv.org/abs/1908.05540)

##### PDF
[http://arxiv.org/pdf/1908.05540](http://arxiv.org/pdf/1908.05540)

