---
layout: post
title: "Online Object Representations with Contrastive Learning"
date: 2019-06-10 22:43:20
categories: arXiv_CV
tags: arXiv_CV
author: S&#xf6;ren Pirk, Mohi Khansari, Yunfei Bai, Corey Lynch, Pierre Sermanet
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a self-supervised approach for learning representations of objects from monocular videos and demonstrate it is particularly useful in situated settings such as robotics. The main contributions of this paper are: 1) a self-supervising objective trained with contrastive learning that can discover and disentangle object attributes from video without using any labels; 2) we leverage object self-supervision for online adaptation: the longer our online model looks at objects in a video, the lower the object identification error, while the offline baseline remains with a large fixed error; 3) to explore the possibilities of a system entirely free of human supervision, we let a robot collect its own data, train on this data with our self-supervise scheme, and then show the robot can point to objects similar to the one presented in front of it, demonstrating generalization of object attributes. An interesting and perhaps surprising finding of this approach is that given a limited set of objects, object correspondences will naturally emerge when using contrastive learning without requiring explicit positive pairs. Videos illustrating online object adaptation and robotic pointing are available at: https://online-objects.github.io/.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.04312](http://arxiv.org/abs/1906.04312)

##### PDF
[http://arxiv.org/pdf/1906.04312](http://arxiv.org/pdf/1906.04312)

