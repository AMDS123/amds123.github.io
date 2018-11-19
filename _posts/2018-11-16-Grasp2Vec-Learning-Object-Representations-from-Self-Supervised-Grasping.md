---
layout: post
title: "Grasp2Vec: Learning Object Representations from Self-Supervised Grasping"
date: 2018-11-16 18:42:02
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Represenation_Learning Relation
author: Eric Jang, Coline Devin, Vincent Vanhoucke, Sergey Levine
mathjax: true
---

* content
{:toc}

##### Abstract
Well structured visual representations can make robot learning faster and can improve generalization. In this paper, we study how we can acquire effective object-centric representations for robotic manipulation tasks without human labeling by using autonomous robot interaction with the environment. Such representation learning methods can benefit from continuous refinement of the representation as the robot collects more experience, allowing them to scale effectively without human intervention. Our representation learning approach is based on object persistence: when a robot removes an object from a scene, the representation of that scene should change according to the features of the object that was removed. We formulate an arithmetic relationship between feature vectors from this observation, and use it to learn a representation of scenes and objects that can then be used to identify object instances, localize them in the scene, and perform goal-directed grasping tasks where the robot must retrieve commanded objects from a bin. The same grasping procedure can also be used to automatically collect training data for our method, by recording images of scenes, grasping and removing an object, and recording the outcome. Our experiments demonstrate that this self-supervised approach for tasked grasping substantially outperforms direct reinforcement learning from images and prior representation learning methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.06964](http://arxiv.org/abs/1811.06964)

##### PDF
[http://arxiv.org/pdf/1811.06964](http://arxiv.org/pdf/1811.06964)

