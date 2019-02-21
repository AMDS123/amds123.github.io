---
layout: post
title: "LOSSGRAD: automatic learning rate in gradient descent"
date: 2019-02-20 17:11:17
categories: arXiv_AI
tags: arXiv_AI Gradient_Descent
author: Bartosz W&#xf3;jcik, &#x141;ukasz Maziarka, Jacek Tabor
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a simple, fast and easy to implement algorithm LOSSGRAD (locally optimal step-size in gradient descent), which automatically modifies the step-size in gradient descent during neural networks training. Given a function $f$, a point $x$, and the gradient $\nabla_x f$ of $f$, we aim to find the step-size $h$ which is (locally) optimal, i.e. satisfies: $$ h=arg\,min_{t \geq 0} f(x-t \nabla_x f). $$ Making use of quadratic approximation, we show that the algorithm satisfies the above assumption. We experimentally show that our method is insensitive to the choice of initial learning rate while achieving results comparable to other methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.07656](http://arxiv.org/abs/1902.07656)

##### PDF
[http://arxiv.org/pdf/1902.07656](http://arxiv.org/pdf/1902.07656)

