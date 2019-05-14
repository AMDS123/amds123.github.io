---
layout: post
title: "Novel Long Short-Term Memory Cell Architectures: Application to Light Field Face Recognition"
date: 2019-05-11 01:38:50
categories: arXiv_CV
tags: arXiv_CV GAN Face RNN Deep_Learning Recognition Face_Recognition
author: Alireza Sepas-Moghaddam, Fernando Pereira, Paulo Lobato Correia
mathjax: true
---

* content
{:toc}

##### Abstract
With the emergence of lenslet light field cameras able to capture rich spatio-angular information from multiple directions, new frontiers in visual recognition performance have been opened. Since multiple 2D viewpoint images can be rendered from a light field, those multiple images, or descriptions extracted from them, can be organized as a pseudo-video sequence so that a LSTM network learns a model describing that sequence. This paper proposes three novel LSTM cell architectures able to create richer and more effective description models for visual recognition tasks, by jointly learning from two sequences simultaneously acquired. The novel key idea is to jointly process two sequences of rendered 2D images or their descriptions, e.g. representing the scene horizontal and vertical parallaxes, and thus with some specific dependency between them, that would not be exploited otherwise. To show the efficiency of the novel LSTM cell architectures, these architectures have been integrated into an end-to-end deep learning face recognition framework, which creates this join spatio-angular light field description. The LSTM network, using the proposed LSTM cell architectures, receives as input a sequence of VGG-Face descriptions computed for parallax related, horizontal and vertical 2D face viewpoint images, derived from the input light field image. A comprehensive evaluation in terms of recognition accuracy, computational complexity, memory efficiency, and parallelization ability has been performed with the IST EURECOM LFFD database using three new and challenging evaluation protocols. The obtained results show the superior performance of the proposed face recognition solutions adopting the novel LSTM cell architectures over ten state-of-the-art benchmarking recognition solutions.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.04421](http://arxiv.org/abs/1905.04421)

##### PDF
[http://arxiv.org/pdf/1905.04421](http://arxiv.org/pdf/1905.04421)

