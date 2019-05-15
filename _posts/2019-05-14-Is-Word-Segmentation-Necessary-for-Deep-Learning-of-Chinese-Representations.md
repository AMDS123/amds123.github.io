---
layout: post
title: "Is Word Segmentation Necessary for Deep Learning of Chinese Representations?"
date: 2019-05-14 11:39:43
categories: arXiv_AI
tags: arXiv_AI Segmentation Text_Classification Classification Deep_Learning Language_Model
author: Yuxian Meng, Xiaoya Li, Xiaofei Sun, Qinghong Han, Arianna Yuan, Jiwei Li
mathjax: true
---

* content
{:toc}

##### Abstract
Segmenting a chunk of text into words is usually the first step of processing Chinese text, but its necessity has rarely been explored. In this paper, we ask the fundamental question of whether Chinese word segmentation (CWS) is necessary for deep learning-based Chinese Natural Language Processing. We benchmark neural word-based models which rely on word segmentation against neural char-based models which do not involve word segmentation in four end-to-end NLP benchmark tasks: language modeling, machine translation, sentence matching/paraphrase and text classification. Through direct comparisons between these two types of models, we find that char-based models consistently outperform word-based models. Based on these observations, we conduct comprehensive experiments to study why word-based models underperform char-based models in these deep learning-based NLP tasks. We show that it is because word-based models are more vulnerable to data sparsity and the presence of out-of-vocabulary (OOV) words, and thus more prone to overfitting. We hope this paper could encourage researchers in the community to rethink the necessity of word segmentation in deep learning-based Chinese Natural Language Processing. \footnote{Yuxian Meng and Xiaoya Li contributed equally to this paper.}

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.05526](https://arxiv.org/abs/1905.05526)

##### PDF
[https://arxiv.org/pdf/1905.05526](https://arxiv.org/pdf/1905.05526)

