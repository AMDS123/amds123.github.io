---
layout: post
title: "Benchmarking Approximate Inference Methods for Neural Structured Prediction"
date: 2019-04-01 23:08:05
categories: arXiv_AI
tags: arXiv_AI Inference Prediction Gradient_Descent
author: Lifu Tu, Kevin Gimpel
mathjax: true
---

* content
{:toc}

##### Abstract
Exact structured inference with neural network scoring functions is computationally challenging but several methods have been proposed for approximating inference. One approach is to perform gradient descent with respect to the output structure directly (Belanger and McCallum, 2016). Another approach, proposed recently, is to train a neural network (an "inference network") to perform inference (Tu and Gimpel, 2018). In this paper, we compare these two families of inference methods on three sequence labeling datasets. We choose sequence labeling because it permits us to use exact inference as a benchmark in terms of speed, accuracy, and search error. Across datasets, we demonstrate that inference networks achieve a better speed/accuracy/search error trade-off than gradient descent, while also being faster than exact inference at similar accuracy levels. We find further benefit by combining inference networks and gradient descent, using the former to provide a warm start for the latter.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.01138](http://arxiv.org/abs/1904.01138)

##### PDF
[http://arxiv.org/pdf/1904.01138](http://arxiv.org/pdf/1904.01138)

