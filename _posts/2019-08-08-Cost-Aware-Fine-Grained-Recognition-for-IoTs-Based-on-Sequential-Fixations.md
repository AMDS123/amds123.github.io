---
layout: post
title: "Cost-Aware Fine-Grained Recognition for IoTs Based on Sequential Fixations"
date: 2019-08-08 10:52:54
categories: arXiv_CV
tags: arXiv_CV Reinforcement_Learning Classification Recognition
author: Hanxiao Wang, Venkatesh Saligrama, Stan Sclaroff, Vitaly Ablavsky
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the problem of fine-grained classification on an edge camera device that has limited power. The edge device must sparingly interact with the cloud to minimize communication bits to conserve power, and the cloud upon receiving the edge inputs returns a classification label. To deal with fine-grained classification, we adopt the perspective of sequential fixation with a foveated field-of-view to model cloud-edge interactions. We propose a novel deep reinforcement learning-based foveation model, DRIFT, that sequentially generates and recognizes mixed-acuity images.Training of DRIFT requires only image-level category labels and encourages fixations to contain task-relevant information, while maintaining data efficiency. Specifically, wetrain a foveation actor network with a novel Deep Deterministic Policy Gradient by Conditioned Critic and Coaching (DDPGC3) algorithm. In addition, we propose to shape the reward to provide informative feedback after each fixation to better guide RL training. We demonstrate the effectiveness of DRIFT on this task by evaluating on five fine-grained classification benchmark datasets, and show that the proposed approach achieves state-of-the-art performance with over 3X reduction in transmitted pixels.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.06868](http://arxiv.org/abs/1811.06868)

##### PDF
[http://arxiv.org/pdf/1811.06868](http://arxiv.org/pdf/1811.06868)

