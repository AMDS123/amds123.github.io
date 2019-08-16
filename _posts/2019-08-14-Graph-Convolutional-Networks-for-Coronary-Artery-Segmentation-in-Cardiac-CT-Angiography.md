---
layout: post
title: "Graph Convolutional Networks for Coronary Artery Segmentation in Cardiac CT Angiography"
date: 2019-08-14 20:48:27
categories: arXiv_CV
tags: arXiv_CV Segmentation Face CNN Prediction Quantitative Detection
author: Jelmer M. Wolterink, Tim Leiner, Ivana I&#x161;gum
mathjax: true
---

* content
{:toc}

##### Abstract
Detection of coronary artery stenosis in coronary CT angiography (CCTA) requires highly personalized surface meshes enclosing the coronary lumen. In this work, we propose to use graph convolutional networks (GCNs) to predict the spatial location of vertices in a tubular surface mesh that segments the coronary artery lumen. Predictions for individual vertex locations are based on local image features as well as on features of neighboring vertices in the mesh graph. The method was trained and evaluated using the publicly available Coronary Artery Stenoses Detection and Quantification Evaluation Framework. Surface meshes enclosing the full coronary artery tree were automatically extracted. A quantitative evaluation on 78 coronary artery segments showed that these meshes corresponded closely to reference annotations, with a Dice similarity coefficient of 0.75/0.73, a mean surface distance of 0.25/0.28 mm, and a Hausdorff distance of 1.53/1.86 mm in healthy/diseased vessel segments. The results showed that inclusion of mesh information in a GCN improves segmentation overlap and accuracy over a baseline model without interaction on the mesh. The results indicate that GCNs allow efficient extraction of coronary artery surface meshes and that the use of GCNs leads to regular and more accurate meshes.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.05343](http://arxiv.org/abs/1908.05343)

##### PDF
[http://arxiv.org/pdf/1908.05343](http://arxiv.org/pdf/1908.05343)

