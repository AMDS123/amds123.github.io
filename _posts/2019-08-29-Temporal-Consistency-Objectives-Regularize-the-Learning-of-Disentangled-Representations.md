---
layout: post
title: "Temporal Consistency Objectives Regularize the Learning of Disentangled Representations"
date: 2019-08-29 16:23:50
categories: arXiv_CV
tags: arXiv_CV Regularization Segmentation Relation
author: Gabriele Valvano, Agisilaos Chartsias, Andrea Leo, Sotirios A. Tsaftaris
mathjax: true
---

* content
{:toc}

##### Abstract
There has been an increasing focus in learning interpretable feature representations, particularly in applications such as medical image analysis that require explainability, whilst relying less on annotated data (since annotations can be tedious and costly). Here we build on recent innovations in style-content representations to learn anatomy, imaging characteristics (appearance) and temporal correlations. By introducing a self-supervised objective of predicting future cardiac phases we improve disentanglement. We propose a temporal transformer architecture that given an image conditioned on phase difference, it predicts a future frame. This forces the anatomical decomposition to be consistent with the temporal cardiac contraction in cine MRI and to have semantic meaning with less need for annotations. We demonstrate that using this regularization, we achieve competitive results and improve semi-supervised segmentation, especially when very few labelled data are available. Specifically, we show Dice increase of up to 19\% and 7\% compared to supervised and semi-supervised approaches respectively on the ACDC dataset. Code is available at: https://github.com/gvalvano/sdtnet .

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.11330](http://arxiv.org/abs/1908.11330)

##### PDF
[http://arxiv.org/pdf/1908.11330](http://arxiv.org/pdf/1908.11330)

