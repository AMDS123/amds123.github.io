---
layout: post
title: "Textured Neural Avatars"
date: 2019-05-21 17:46:16
categories: arXiv_AI
tags: arXiv_AI Face CNN Deep_Learning
author: Aliaksandra Shysheya (Samsung AI Center, Skolkovo Institute of Science and Technology), Egor Zakharov (Samsung AI Center, Skolkovo Institute of Science and Technology), Kara-Ali Aliev (Samsung AI Center), Renat Bashirov (Samsung AI Center), Egor Burkov (Samsung AI Center, Skolkovo Institute of Science and Technology), Karim Iskakov (Samsung AI Center), Aleksei Ivakhnenko (Samsung AI Center), Yury Malkov (Samsung AI Center), Igor Pasechnik (Samsung AI Center), Dmitry Ulyanov (Samsung AI Center, Skolkovo Institute of Science and Technology), Alexander Vakhitov (Samsung AI Center, Skolkovo Institute of Science and Technology), Victor Lempitsky (Samsung AI Center, Skolkovo Institute of Science and Technology)
mathjax: true
---

* content
{:toc}

##### Abstract
We present a system for learning full-body neural avatars, i.e. deep networks that produce full-body renderings of a person for varying body pose and camera position. Our system takes the middle path between the classical graphics pipeline and the recent deep learning approaches that generate images of humans using image-to-image translation. In particular, our system estimates an explicit two-dimensional texture map of the model surface. At the same time, it abstains from explicit shape modeling in 3D. Instead, at test time, the system uses a fully-convolutional network to directly map the configuration of body feature points w.r.t. the camera to the 2D texture coordinates of individual pixels in the image frame. We show that such a system is capable of learning to generate realistic renderings while being trained on videos annotated with 3D poses and foreground masks. We also demonstrate that maintaining an explicit texture representation helps our system to achieve better generalization compared to systems that use direct image-to-image translation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.08776](http://arxiv.org/abs/1905.08776)

##### PDF
[http://arxiv.org/pdf/1905.08776](http://arxiv.org/pdf/1905.08776)

