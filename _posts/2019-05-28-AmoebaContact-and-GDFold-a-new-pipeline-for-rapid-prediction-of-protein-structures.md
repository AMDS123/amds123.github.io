---
layout: post
title: "AmoebaContact and GDFold: a new pipeline for rapid prediction of protein structures"
date: 2019-05-28 06:54:24
categories: arXiv_CV
tags: arXiv_CV Prediction Gradient_Descent
author: Wenzhi Mao, Wenze Ding, Haipeng Gong
mathjax: true
---

* content
{:toc}

##### Abstract
Native contacts between residues could be predicted from the amino acid sequence of proteins, and the predicted contact information could assist the de novo protein structure prediction. Here, we present a novel pipeline of a residue contact predictor AmoebaContact and a contact-assisted folder GDFold for rapid protein structure prediction. Unlike mainstream contact predictors that utilize human-designed neural networks, AmoebaContact adopts a set of network architectures that are found as optimal for contact prediction through automatic searching and predicts the residue contacts at a series of cutoffs. Different from conventional contact-assisted folders that only use top-scored contact pairs, GDFold considers all residue pairs from the prediction results of AmoebaContact in a differentiable loss function and optimizes the atom coordinates using the gradient descent algorithm. Combination of AmoebaContact and GDFold allows quick reconstruction of the protein structure, with comparable model quality to the state-of-the-art protein structure prediction methods.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.11640](https://arxiv.org/abs/1905.11640)

##### PDF
[https://arxiv.org/pdf/1905.11640](https://arxiv.org/pdf/1905.11640)

