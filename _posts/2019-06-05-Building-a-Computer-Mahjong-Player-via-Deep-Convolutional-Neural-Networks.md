---
layout: post
title: "Building a Computer Mahjong Player via Deep Convolutional Neural Networks"
date: 2019-06-05 17:07:08
categories: arXiv_AI
tags: arXiv_AI Knowledge CNN Deep_Learning
author: Shiqi Gao, Fuminori Okuya, Yoshihiro Kawahara, Yoshimasa Tsuruoka
mathjax: true
---

* content
{:toc}

##### Abstract
The evaluation function for imperfect information games is always hard to define but owns a significant impact on the playing strength of a program. Deep learning has made great achievements these years, and already exceeded the top human players' level even in the game of Go. In this paper, we introduce a new data model to represent the available imperfect information on the game table, and construct a well-designed convolutional neural network for game record training. We choose the accuracy of tile discarding which is also called as the agreement rate as the benchmark for this study. Our accuracy on test data reaches 70.44%, while the state-of-art baseline is 62.1% reported by Mizukami and Tsuruoka (2015), and is significantly higher than previous trials using deep learning, which shows the promising potential of our new model. For the AI program building, besides the tile discarding strategy, we adopt similar predicting strategies for other actions such as stealing (pon, chi, and kan) and riichi. With the simple combination of these several predicting networks and without any knowledge about the concrete rules of the game, a strength evaluation is made for the resulting program on the largest Japanese Mahjong site `Tenhou'gm. The program has achieved a rating of around 1850, which is significantly higher than that of an average human player and of programs among past studies.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.02146](http://arxiv.org/abs/1906.02146)

##### PDF
[http://arxiv.org/pdf/1906.02146](http://arxiv.org/pdf/1906.02146)

