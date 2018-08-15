---
layout: post
title: "MentorNet: Learning Data-Driven Curriculum for Very Deep Neural Networks on Corrupted Labels"
date: 2018-08-13 21:27:39
categories: arXiv_CV
tags: arXiv_CV Knowledge
author: Lu Jiang, Zhengyuan Zhou, Thomas Leung, Li-Jia Li, Li Fei-Fei
mathjax: true
---

* content
{:toc}

##### Abstract
Recent deep networks are capable of memorizing the entire data even when the labels are completely random. To overcome the overfitting on corrupted labels, we propose a novel technique of learning another neural network, called MentorNet, to supervise the training of the base deep networks, namely, StudentNet. During training, MentorNet provides a curriculum (sample weighting scheme) for StudentNet to focus on the sample the label of which is probably correct. Unlike the existing curriculum that is usually predefined by human experts, MentorNet learns a data-driven curriculum dynamically with StudentNet. Experimental results demonstrate that our approach can significantly improve the generalization performance of deep networks trained on corrupted training data. Notably, to the best of our knowledge, we achieve the best-published result on WebVision, a large benchmark containing 2.2 million images of real-world noisy labels. The code are at https://github.com/google/mentornet

##### Abstract (translated by Google)
即使标签完全随机，最近的深度网络也能够记忆整个数据。为了克服对损坏标签的过度拟合，我们提出了一种新的技术，即学习另一个神经网络，称为MentorNet，来监督基础深度网络即StudentNet的训练。在培训期间，MentorNet为StudentNet提供课程（样本加权方案），专注于标签可能正确的样本。与通常由人类专家预定义的现有课程不同，MentorNet使用StudentNet动态学习数据驱动的课程。实验结果表明，我们的方法可以显着提高训练过程中受损训练数据的深度网络的泛化性能。值得注意的是，据我们所知，我们在WebVision上获得了最佳发布的结果，这是一个包含220万个真实噪声标签图像的大型基准测试。代码位于https://github.com/google/mentornet

##### URL
[http://arxiv.org/abs/1712.05055](http://arxiv.org/abs/1712.05055)

##### PDF
[http://arxiv.org/pdf/1712.05055](http://arxiv.org/pdf/1712.05055)

