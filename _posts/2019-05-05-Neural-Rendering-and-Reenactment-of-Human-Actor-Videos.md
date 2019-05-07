---
layout: post
title: "Neural Rendering and Reenactment of Human Actor Videos"
date: 2019-05-05 08:55:03
categories: arXiv_CV
tags: arXiv_CV Adversarial
author: Lingjie Liu, Weipeng Xu, Michael Zollhoefer, Hyeongwoo Kim, Florian Bernard, Marc Habermann, Wenping Wang, Christian Theobalt
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a method for generating video-realistic animations of real humans under user control. In contrast to conventional human character rendering, we do not require the availability of a production-quality photo-realistic 3D model of the human, but instead rely on a video sequence in conjunction with a (medium-quality) controllable 3D template model of the person. With that, our approach significantly reduces production cost compared to conventional rendering approaches based on production-quality 3D models, and can also be used to realistically edit existing videos. Technically, this is achieved by training a neural network that translates simple synthetic images of a human character into realistic imagery. For training our networks, we first track the 3D motion of the person in the video using the template model, and subsequently generate a synthetically rendered version of the video. These images are then used to train a conditional generative adversarial network that translates synthetic images of the 3D model into realistic imagery of the human. We evaluate our method for the reenactment of another person that is tracked in order to obtain the motion data, and show video results generated from artist-designed skeleton motion. Our results outperform the state-of-the-art in learning-based human image synthesis. Project page: <a href="http://gvv.mpi-inf.mpg.de/projects/wxu/HumanReenactment/">this http URL</a>

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.03658](http://arxiv.org/abs/1809.03658)

##### PDF
[http://arxiv.org/pdf/1809.03658](http://arxiv.org/pdf/1809.03658)

