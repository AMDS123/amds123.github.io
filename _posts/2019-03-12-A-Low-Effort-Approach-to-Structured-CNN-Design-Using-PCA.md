---
layout: post
title: "A Low Effort Approach to Structured CNN Design Using PCA"
date: 2019-03-12 02:07:16
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Isha Garg, Priyadarshini Panda, Kaushik Roy
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning models hold state of the art performance in many fields, yet their design is still based on heuristics or grid search methods. This work proposes a method to analyze a trained network and deduce an optimized, compressed architecture that preserves accuracy while keeping computational costs tractable. Model compression is an active field of research that targets the problem of realizing deep learning models in hardware. However, most pruning methodologies tend to be experimental, requiring large compute and time intensive iterations of retraining the entire network. We introduce structure into model design by proposing a single shot analysis of a trained network that frames model compression as a dimensionality reduction problem. The proposed method analyzes the activations of each layer simultaneously and looks at the dimensionality of the space described by the filters generating these activations. It optimizes the architecture in terms of number of layers, and number of filters per layer without any iterative retraining procedures, making it a viable, low effort technique to design efficient networks. We demonstrate the proposed methodology on AlexNet and VGG style networks on the CIFAR-10, CIFAR-100 and ImageNet datasets, and successfully achieve an optimized architecture, reducing both depth and layer-wise width while trading off less than 1% accuracy.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1812.06224](https://arxiv.org/abs/1812.06224)

##### PDF
[https://arxiv.org/pdf/1812.06224](https://arxiv.org/pdf/1812.06224)

