---
layout: post
title: "Deep learning investigation for chess player attention prediction using eye-tracking and game data"
date: 2019-04-17 09:31:37
categories: arXiv_CV
tags: arXiv_CV Salient Attention Tracking CNN Deep_Learning Prediction Relation
author: Justin Le Louedec (PERVASIVE), Thomas Guntz (PERVASIVE), James Crowley (PERVASIVE), Dominique Vaufreydaz (PERVASIVE)
mathjax: true
---

* content
{:toc}

##### Abstract
This article reports on an investigation of the use of convolutional neural networks to predict the visual attention of chess players. The visual attention model described in this article has been created to generate saliency maps that capture hierarchical and spatial features of chessboard, in order to predict the probability fixation for individual pixels Using a skip-layer architecture of an autoencoder, with a unified decoder, we are able to use multiscale features to predict saliency of part of the board at different scales, showing multiple relations between pieces. We have used scan path and fixation data from players engaged in solving chess problems, to compute 6600 saliency maps associated to the corresponding chess piece configurations. This corpus is completed with synthetically generated data from actual games gathered from an online chess platform. Experiments realized using both scan-paths from chess players and the CAT2000 saliency dataset of natural images, highlights several results. Deep features, pretrained on natural images, were found to be helpful in training visual attention prediction for chess. The proposed neural network architecture is able to generate meaningful saliency maps on unseen chess configurations with good scores on standard metrics. This work provides a baseline for future work on visual attention prediction in similar contexts.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08155](http://arxiv.org/abs/1904.08155)

##### PDF
[http://arxiv.org/pdf/1904.08155](http://arxiv.org/pdf/1904.08155)

