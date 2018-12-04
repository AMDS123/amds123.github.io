---
layout: post
title: "Visual Foresight: Model-Based Deep Reinforcement Learning for Vision-Based Robotic Control"
date: 2018-12-03 06:06:25
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Deep_Learning
author: Frederik Ebert, Chelsea Finn, Sudeep Dasari, Annie Xie, Alex Lee, Sergey Levine
mathjax: true
---

* content
{:toc}

##### Abstract
Deep reinforcement learning (RL) algorithms can learn complex robotic skills from raw sensory inputs, but have yet to achieve the kind of broad generalization and applicability demonstrated by deep learning methods in supervised domains. We present a deep RL method that is practical for real-world robotics tasks, such as robotic manipulation, and generalizes effectively to never-before-seen tasks and objects. In these settings, ground truth reward signals are typically unavailable, and we therefore propose a self-supervised model-based approach, where a predictive model learns to directly predict the future from raw sensory readings, such as camera images. At test time, we explore three distinct goal specification methods: designated pixels, where a user specifies desired object manipulation tasks by selecting particular pixels in an image and corresponding goal positions, goal images, where the desired goal state is specified with an image, and image classifiers, which define spaces of goal states. Our deep predictive models are trained using data collected autonomously and continuously by a robot interacting with hundreds of objects, without human supervision. We demonstrate that visual MPC can generalize to never-before-seen objects---both rigid and deformable---and solve a range of user-defined object manipulation tasks using the same model.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.00568](http://arxiv.org/abs/1812.00568)

##### PDF
[http://arxiv.org/pdf/1812.00568](http://arxiv.org/pdf/1812.00568)

