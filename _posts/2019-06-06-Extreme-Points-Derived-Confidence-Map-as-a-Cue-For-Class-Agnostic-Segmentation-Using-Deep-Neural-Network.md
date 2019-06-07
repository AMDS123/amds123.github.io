---
layout: post
title: "Extreme Points Derived Confidence Map as a Cue For Class-Agnostic Segmentation Using Deep Neural Network"
date: 2019-06-06 05:19:22
categories: arXiv_CV
tags: arXiv_CV Segmentation Quantitative
author: Shadab Khan, Ahmed H. Shahin, Javier Villafruela, Jianbing Shen, Ling Shao
mathjax: true
---

* content
{:toc}

##### Abstract
To automate the process of segmenting an anatomy of interest, we can learn a model from previously annotated data. The learning-based approach uses annotations to train a model that tries to emulate the expert labeling on a new data set. While tremendous progress has been made using such approaches, labeling of medical images remains a time-consuming and expensive task. In this paper, we evaluate the utility of extreme points in learning to segment. Specifically, we propose a novel approach to compute a confidence map from extreme points that quantitatively encodes the priors derived from extreme points. We use the confidence map as a cue to train a deep neural network based on ResNet-101 and PSP module to develop a class-agnostic segmentation model that outperforms state-of-the-art method that employs extreme points as a cue. Further, we evaluate a realistic use-case by using our model to generate training data for supervised learning (U-Net) and observed that U-Net performs comparably when trained with either the generated data or the ground truth data. These findings suggest that models trained using cues can be used to generate reliable training data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.02421](http://arxiv.org/abs/1906.02421)

##### PDF
[http://arxiv.org/pdf/1906.02421](http://arxiv.org/pdf/1906.02421)

