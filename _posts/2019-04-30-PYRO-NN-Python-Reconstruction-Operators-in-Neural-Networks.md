---
layout: post
title: "PYRO-NN: Python Reconstruction Operators in Neural Networks"
date: 2019-04-30 16:12:55
categories: arXiv_CV
tags: arXiv_CV Embedding Deep_Learning
author: Christopher Syben, Markus Michen, Bernhard Stimpel, Stephan Seitz, Stefan Ploner, Andreas K. Maier
mathjax: true
---

* content
{:toc}

##### Abstract
Purpose: Recently, several attempts were conducted to transfer deep learning to medical image reconstruction. An increasingly number of publications follow the concept of embedding the CT reconstruction as a known operator into a neural network. However, most of the approaches presented lack an efficient CT reconstruction framework fully integrated into deep learning environments. As a result, many approaches are forced to use workarounds for mathematically unambiguously solvable problems. Methods: PYRO-NN is a generalized framework to embed known operators into the prevalent deep learning framework Tensorflow. The current status includes state-of-the-art parallel-, fan- and cone-beam projectors and back-projectors accelerated with CUDA provided as Tensorflow layers. On top, the framework provides a high level Python API to conduct FBP and iterative reconstruction experiments with data from real CT systems. Results: The framework provides all necessary algorithms and tools to design end-to-end neural network pipelines with integrated CT reconstruction algorithms. The high level Python API allows a simple use of the layers as known from Tensorflow. To demonstrate the capabilities of the layers, the framework comes with three baseline experiments showing a cone-beam short scan FDK reconstruction, a CT reconstruction filter learning setup, and a TV regularized iterative reconstruction. All algorithms and tools are referenced to a scientific publication and are compared to existing non deep learning reconstruction frameworks. The framework is available as open-source software at \url{https://github.com/csyben/PYRO-NN}. Conclusions: PYRO-NN comes with the prevalent deep learning framework Tensorflow and allows to setup end-to-end trainable neural networks in the medical image reconstruction context. We believe that the framework will be a step towards reproducible research

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.13342](http://arxiv.org/abs/1904.13342)

##### PDF
[http://arxiv.org/pdf/1904.13342](http://arxiv.org/pdf/1904.13342)

