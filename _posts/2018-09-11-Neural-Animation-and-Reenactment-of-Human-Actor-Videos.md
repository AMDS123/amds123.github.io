---
layout: post
title: "Neural Animation and Reenactment of Human Actor Videos"
date: 2018-09-11 02:29:26
categories: arXiv_CV
tags: arXiv_CV Adversarial
author: Lingjie Liu, Weipeng Xu, Michael Zollhoefer, Hyeongwoo Kim, Florian Bernard, Marc Habermann, Wenping Wang, Christian Theobalt
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a method for generating (near) video-realistic animations of real humans under user control. In contrast to conventional human character rendering, we do not require the availability of a production-quality photo-realistic 3D model of the human, but instead rely on a video sequence in conjunction with a (medium-quality) controllable 3D template model of the person. With that, our approach significantly reduces production cost compared to conventional rendering approaches based on production-quality 3D models, and can also be used to realistically edit existing videos. Technically, this is achieved by training a neural network that translates simple synthetic images of a human character into realistic imagery. For training our networks, we first track the 3D motion of the person in the video using the template model, and subsequently generate a synthetically rendered version of the video. These images are then used to train a conditional generative adversarial network that translates synthetic images of the 3D model into realistic imagery of the human. We evaluate our method for the reenactment of another person that is tracked in order to obtain the motion data, and show video results generated from artist-designed skeleton motion. Our results outperform the state-of-the-art in learning-based human image synthesis. Project page: <a href="http://gvv.mpi-inf.mpg.de/projects/wxu/HumanReenactment/">this http URL</a>

##### Abstract (translated by Google)
我们提出了一种在用户控制下生成（近）真实人类视频逼真动画的方法。与传统的人物角色渲染相比，我们不需要人类可以获得生产质量逼真的3D模型，而是依赖于视频序列和（中等质量）可控制的3D模板模型。人。这样，与基于生产质量3D模型的传统渲染方法相比，我们的方法显着降低了生产成本，并且还可用于实际编辑现有视频。从技术上讲，这是通过训练神经网络来实现的，神经网络将人类角色的简单合成图像转换为逼真的图像。为了训练我们的网络，我们首先使用模板模型跟踪视频中人物的3D运动，然后生成视频的综合渲染版本。然后，这些图像用于训练条件生成对抗网络，该网络将3D模型的合成图像转换为人的真实图像。我们评估我们为了获得运动数据而被跟踪的另一个人的重演方法，并显示由艺术家设计的骨架运动产生的视频结果。我们的结果优于基于学习的人类图像合成的最新技术。项目页面：<a href="http://gvv.mpi-inf.mpg.de/projects/wxu/HumanReenactment/">此http网址</a>

##### URL
[http://arxiv.org/abs/1809.03658](http://arxiv.org/abs/1809.03658)

##### PDF
[http://arxiv.org/pdf/1809.03658](http://arxiv.org/pdf/1809.03658)

