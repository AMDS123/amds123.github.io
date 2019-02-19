---
layout: post
title: "Learning Quickly to Plan Quickly Using Modular Meta-Learning"
date: 2019-02-16 03:12:51
categories: arXiv_AI
tags: arXiv_AI
author: Rohan Chitnis, Leslie Pack Kaelbling, Tom&#xe1;s Lozano-P&#xe9;rez
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-object manipulation problems in continuous state and action spaces can be solved by planners that search over sampled values for the continuous parameters of operators. The efficiency of these planners depends critically on the effectiveness of the samplers used, but effective sampling in turn depends on details of the robot, environment, and task. Our strategy is to learn functions called "specializers" that generate values for continuous operator parameters, given a state description and values for the discrete parameters. Rather than trying to learn a single specializer for each operator from large amounts of data on a single task, we take a modular meta-learning approach. We train on multiple tasks and learn a variety of specializers that, on a new task, can be quickly adapted using relatively little data -- thus, our system "learns quickly to plan quickly" using these specializers. We validate our approach experimentally in simulated 3D pick-and-place tasks with continuous state and action spaces. Visit <a href="http://tinyurl.com/chitnis-icra-19">this http URL</a> for a supplementary video.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.07878](http://arxiv.org/abs/1809.07878)

##### PDF
[http://arxiv.org/pdf/1809.07878](http://arxiv.org/pdf/1809.07878)

