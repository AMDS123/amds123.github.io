---
layout: post
title: "Extracting Scientific Figures with Distantly Supervised Neural Networks"
date: 2018-05-30 19:13:53
categories: arXiv_CV
tags: arXiv_CV Caption Detection
author: Noah Siegel, Nicholas Lourie, Russell Power, Waleed Ammar
mathjax: true
---

* content
{:toc}

##### Abstract
Non-textual components such as charts, diagrams and tables provide key information in many scientific documents, but the lack of large labeled datasets has impeded the development of data-driven methods for scientific figure extraction. In this paper, we induce high-quality training labels for the task of figure extraction in a large number of scientific documents, with no human intervention. To accomplish this we leverage the auxiliary data provided in two large web collections of scientific documents (arXiv and PubMed) to locate figures and their associated captions in the rasterized PDF. We share the resulting dataset of over 5.5 million induced labels---4,000 times larger than the previous largest figure extraction dataset---with an average precision of 96.8%, to enable the development of modern data-driven methods for this task. We use this dataset to train a deep neural network for end-to-end figure detection, yielding a model that can be more easily extended to new domains compared to previous work. The model was successfully deployed in Semantic Scholar, a large-scale academic search engine, and used to extract figures in 13 million scientific documents.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1804.02445](https://arxiv.org/abs/1804.02445)

##### PDF
[https://arxiv.org/pdf/1804.02445](https://arxiv.org/pdf/1804.02445)

