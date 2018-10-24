---
layout: post
title: "Interpretable LSTMs For Whole-Brain Neuroimaging Analyses"
date: 2018-10-23 16:23:27
categories: arXiv_CV
tags: arXiv_CV RNN Relation
author: Armin W. Thomas, Hauke R. Heekeren, Klaus-Robert M&#xfc;ller, Wojciech Samek
mathjax: true
---

* content
{:toc}

##### Abstract
The analysis of neuroimaging data poses several strong challenges, in particular, due to its high dimensionality, its strong spatio-temporal correlation and the comparably small sample sizes of the respective datasets. To address these challenges, conventional decoding approaches such as the searchlight reduce the complexity of the decoding problem by considering local clusters of voxels only. Thereby, neglecting the distributed spatial patterns of brain activity underlying many cognitive states. In this work, we introduce the DLight framework, which overcomes these challenges by utilizing a long short-term memory unit (LSTM) based deep neural network architecture to analyze the spatial dependency structure of whole-brain fMRI data. In order to maintain interpretability of the neuroimaging data, we adapt the layer-wise relevance propagation (LRP) method. Thereby, we enable the neuroscientist user to study the learned association of the LSTM between the data and the cognitive state of the individual. We demonstrate the versatility of DLight by applying it to a large fMRI dataset of the Human Connectome Project. We show that the decoding performance of our method scales better with large datasets, and moreover outperforms conventional decoding approaches, while still detecting physiologically appropriate brain areas for the cognitive states classified. We also demonstrate that DLight is able to detect these areas on several levels of data granularity (i.e., group, subject, trial, time point).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.09945](http://arxiv.org/abs/1810.09945)

##### PDF
[http://arxiv.org/pdf/1810.09945](http://arxiv.org/pdf/1810.09945)

