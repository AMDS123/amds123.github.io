---
layout: post
title: "Trading-off Accuracy and Energy of Deep Inference on Embedded Systems: A Co-Design Approach"
date: 2019-01-29 22:07:41
categories: arXiv_CV
tags: arXiv_CV Image_Classification Optimization Inference Classification Prediction
author: Nitthilan Kannappan Jayakodi, Anwesha Chatterjee, Wonje Choi, Janardhan Rao Doppa, Partha Pratim Pande
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks have seen tremendous success for different modalities of data including images, videos, and speech. This success has led to their deployment in mobile and embedded systems for real-time applications. However, making repeated inferences using deep networks on embedded systems poses significant challenges due to constrained resources (e.g., energy and computing power). To address these challenges, we develop a principled co-design approach. Building on prior work, we develop a formalism referred to as Coarse-to-Fine Networks (C2F Nets) that allow us to employ classifiers of varying complexity to make predictions. We propose a principled optimization algorithm to automatically configure C2F Nets for a specified trade-off between accuracy and energy consumption for inference. The key idea is to select a classifier on-the-fly whose complexity is proportional to the hardness of the input example: simple classifiers for easy inputs and complex classifiers for hard inputs. We perform comprehensive experimental evaluation using four different C2F Net architectures on multiple real-world image classification tasks. Our results show that optimized C2F Net can reduce the Energy Delay Product (EDP) by 27 to 60 percent with no loss in accuracy when compared to the baseline solution, where all predictions are made using the most complex classifier in C2F Net.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.10584](http://arxiv.org/abs/1901.10584)

##### PDF
[http://arxiv.org/pdf/1901.10584](http://arxiv.org/pdf/1901.10584)

