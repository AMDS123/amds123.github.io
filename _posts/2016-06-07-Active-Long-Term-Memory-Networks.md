---
layout: post
title: "Active Long Term Memory Networks"
date: 2016-06-07 23:43:42
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN Inference Deep_Learning Memory_Networks Recognition
author: Tommaso Furlanello, Jiaping Zhao, Andrew M. Saxe, Laurent Itti, Bosco S. Tjan
mathjax: true
---

* content
{:toc}

##### Abstract
Continual Learning in artificial neural networks suffers from interference and forgetting when different tasks are learned sequentially. This paper introduces the Active Long Term Memory Networks (A-LTM), a model of sequential multi-task deep learning that is able to maintain previously learned association between sensory input and behavioral output while acquiring knew knowledge. A-LTM exploits the non-convex nature of deep neural networks and actively maintains knowledge of previously learned, inactive tasks using a distillation loss. Distortions of the learned input-output map are penalized but hidden layers are free to transverse towards new local optima that are more favorable for the multi-task objective. We re-frame the McClelland's seminal Hippocampal theory with respect to Catastrophic Inference (CI) behavior exhibited by modern deep architectures trained with back-propagation and inhomogeneous sampling of latent factors across epochs. We present empirical results of non-trivial CI during continual learning in Deep Linear Networks trained on the same task, in Convolutional Neural Networks when the task shifts from predicting semantic to graphical factors and during domain adaptation from simple to complex environments. We present results of the A-LTM model's ability to maintain viewpoint recognition learned in the highly controlled iLab-20M dataset with 10 object categories and 88 camera viewpoints, while adapting to the unstructured domain of Imagenet with 1,000 object categories.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1606.02355](https://arxiv.org/abs/1606.02355)

##### PDF
[https://arxiv.org/pdf/1606.02355](https://arxiv.org/pdf/1606.02355)

