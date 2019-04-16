---
layout: post
title: "Protein identification with deep learning: from abc to xyz"
date: 2017-10-08 01:23:18
categories: arXiv_CV
tags: arXiv_CV GAN Caption CNN RNN Deep_Learning
author: Ngoc Hieu Tran, Zachariah Levine, Lei Xin, Baozhen Shan, Ming Li
mathjax: true
---

* content
{:toc}

##### Abstract
Proteins are the main workhorses of biological functions in a cell, a tissue, or an organism. Identification and quantification of proteins in a given sample, e.g. a cell type under normal/disease conditions, are fundamental tasks for the understanding of human health and disease. In this paper, we present DeepNovo, a deep learning-based tool to address the problem of protein identification from tandem mass spectrometry data. The idea was first proposed in the context of de novo peptide sequencing [1] in which convolutional neural networks and recurrent neural networks were applied to predict the amino acid sequence of a peptide from its spectrum, a similar task to generating a caption from an image. We further develop DeepNovo to perform sequence database search, the main technique for peptide identification that greatly benefits from numerous existing protein databases. We combine two modules de novo sequencing and database search into a single deep learning framework for peptide identification, and integrate de Bruijn graph assembly technique to offer a complete solution to reconstruct protein sequences from tandem mass spectrometry data. This paper describes a comprehensive protocol of DeepNovo for protein identification, including training neural network models, dynamic programming search, database querying, estimation of false discovery rate, and de Bruijn graph assembly. Training and testing data, model implementations, and comprehensive tutorials in form of IPython notebooks are available in our GitHub repository (this https URL).

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1710.02765](https://arxiv.org/abs/1710.02765)

##### PDF
[https://arxiv.org/pdf/1710.02765](https://arxiv.org/pdf/1710.02765)

