---
layout: post
title: "Analyzing Neuroimaging Data Through Recurrent Deep Learning Models"
date: 2019-04-05 07:31:32
categories: arXiv_CV
tags: arXiv_CV RNN Deep_Learning
author: Armin W. Thomas, Hauke R. Heekeren, Klaus-Robert M&#xfc;ller, Wojciech Samek
mathjax: true
---

* content
{:toc}

##### Abstract
The application of deep learning (DL) models to neuroimaging data poses several challenges, due to the high dimensionality, low sample size and complex temporo-spatial dependency structure of these datasets. Even further, DL models act as as black-box models, impeding insight into the association of cognitive state and brain activity. To approach these challenges, we introduce the DeepLight framework, which utilizes long short-term memory (LSTM) based DL models to analyze whole-brain functional Magnetic Resonance Imaging (fMRI) data. To decode a cognitive state (e.g., seeing the image of a house), DeepLight separates the fMRI volume into a sequence of axial brain slices, which is then sequentially processed by an LSTM. To maintain interpretability, DeepLight adapts the layer-wise relevance propagation (LRP) technique. Thereby, decomposing its decoding decision into the contributions of the single input voxels to this decision. Importantly, the decomposition is performed on the level of single fMRI volumes, enabling DeepLight to study the associations between cognitive state and brain activity on several levels of data granularity, from the level of the group down to the level of single time points. To demonstrate the versatility of DeepLight, we apply it to a large fMRI dataset of the Human Connectome Project. We show that DeepLight outperforms conventional approaches of uni- and multivariate fMRI analysis in decoding the cognitive states and in identifying the physiologically appropriate brain regions associated with these states. We further demonstrate DeepLight's ability to study the fine-grained temporo-spatial variability of brain activity over sequences of single fMRI samples.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.09945](http://arxiv.org/abs/1810.09945)

##### PDF
[http://arxiv.org/pdf/1810.09945](http://arxiv.org/pdf/1810.09945)

