---
layout: post
title: "Multimodal Interaction-aware Motion Prediction for Autonomous Street Crossing"
date: 2019-07-01 13:47:16
categories: arXiv_CV
tags: arXiv_CV CNN Prediction Recognition
author: Noha Radwan, Abhinav Valada, Wolfram Burgard
mathjax: true
---

* content
{:toc}

##### Abstract
For mobile robots navigating on sidewalks, it is essential to be able to safely cross street intersections. Most existing approaches rely on the recognition of the traffic light signal to make an informed crossing decision. Although these approaches have been crucial enablers for urban navigation, the capabilities of robots employing such approaches are still limited to navigating only on streets containing signalized intersections. In this paper, we address this challenge and propose a multimodal convolutional neural network framework to predict the safety of a street intersection for crossing. Our architecture consists of two subnetworks; an interaction-aware trajectory estimation stream IA-TCNN, that predicts the future states of all observed traffic participants in the scene, and a traffic light recognition stream AtteNet. Our IA-TCNN utilizes dilated causal convolutions to model the behavior of the observable dynamic agents in the scene without explicitly assigning priorities to the interactions among them. While AtteNet utilizes Squeeze-Excitation blocks to learn a content-aware mechanism for selecting the relevant features from the data, thereby improving the noise robustness. Learned representations from the traffic light recognition stream are fused with the estimated trajectories from the motion prediction stream to learn the crossing decision. Furthermore, we extend our previously introduced Freiburg Street Crossing dataset with sequences captured at different types of intersections, demonstrating complex interactions among the traffic participants. Extensive experimental evaluations on public benchmark datasets and our proposed dataset demonstrate that our network achieves state-of-the-art performance for each of the subtasks, as well as for the crossing safety prediction.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1808.06887](http://arxiv.org/abs/1808.06887)

##### PDF
[http://arxiv.org/pdf/1808.06887](http://arxiv.org/pdf/1808.06887)

