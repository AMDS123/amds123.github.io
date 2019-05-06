---
layout: post
title: "CSGNet: Neural Shape Parser for Constructive Solid Geometry"
date: 2018-03-31 18:03:22
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Gopal Sharma, Rishabh Goyal, Difan Liu, Evangelos Kalogerakis, Subhransu Maji
mathjax: true
---

* content
{:toc}

##### Abstract
We present a neural architecture that takes as input a 2D or 3D shape and outputs a program that generates the shape. The instructions in our program are based on constructive solid geometry principles, i.e., a set of boolean operations on shape primitives defined recursively. Bottom-up techniques for this shape parsing task rely on primitive detection and are inherently slow since the search space over possible primitive combinations is large. In contrast, our model uses a recurrent neural network that parses the input shape in a top-down manner, which is significantly faster and yields a compact and easy-to-interpret sequence of modeling instructions. Our model is also more effective as a shape detector compared to existing state-of-the-art detection techniques. We finally demonstrate that our network can be trained on novel datasets without ground-truth program annotations through policy gradient techniques.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1712.08290](https://arxiv.org/abs/1712.08290)

##### PDF
[https://arxiv.org/pdf/1712.08290](https://arxiv.org/pdf/1712.08290)

