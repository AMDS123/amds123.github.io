---
layout: post
title: "Face-to-Parameter Translation for Game Character Auto-Creation"
date: 2019-09-03 11:05:19
categories: arXiv_CV
tags: arXiv_CV Face Style_Transfer Optimization Gradient_Descent
author: Tianyang Shi (1), Yi Yuan (1), Changjie Fan (1), Zhengxia Zou (2), Zhenwei Shi (3), Yong Liu (4) ((1) NetEase Fuxi AI Lab, (2) University of Michigan, (3) Beihang University, (4) Zhejiang University)
mathjax: true
---

* content
{:toc}

##### Abstract
Character customization system is an important component in Role-Playing Games (RPGs), where players are allowed to edit the facial appearance of their in-game characters with their own preferences rather than using default templates. This paper proposes a method for automatically creating in-game characters of players according to an input face photo. We formulate the above "artistic creation" process under a facial similarity measurement and parameter searching paradigm by solving an optimization problem over a large set of physically meaningful facial parameters. To effectively minimize the distance between the created face and the real one, two loss functions, i.e. a "discriminative loss" and a "facial content loss", are specifically designed. As the rendering process of a game engine is not differentiable, a generative network is further introduced as an "imitator" to imitate the physical behavior of the game engine so that the proposed method can be implemented under a neural style transfer framework and the parameters can be optimized by gradient descent. Experimental results demonstrate that our method achieves a high degree of generation similarity between the input face photo and the created in-game character in terms of both global appearance and local details. Our method has been deployed in a new game last year and has now been used by players over 1 million times.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1909.01064](https://arxiv.org/abs/1909.01064)

##### PDF
[https://arxiv.org/pdf/1909.01064](https://arxiv.org/pdf/1909.01064)

