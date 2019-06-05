---
layout: post
title: "Text-based Editing of Talking-head Video"
date: 2019-06-04 15:35:16
categories: arXiv_CV
tags: arXiv_CV Face Optimization
author: Ohad Fried, Ayush Tewari, Michael Zollh&#xf6;fer, Adam Finkelstein, Eli Shechtman, Dan B Goldman, Kyle Genova, Zeyu Jin, Christian Theobalt, Maneesh Agrawala
mathjax: true
---

* content
{:toc}

##### Abstract
Editing talking-head video to change the speech content or to remove filler words is challenging. We propose a novel method to edit talking-head video based on its transcript to produce a realistic output video in which the dialogue of the speaker has been modified, while maintaining a seamless audio-visual flow (i.e. no jump cuts). Our method automatically annotates an input talking-head video with phonemes, visemes, 3D face pose and geometry, reflectance, expression and scene illumination per frame. To edit a video, the user has to only edit the transcript, and an optimization strategy then chooses segments of the input corpus as base material. The annotated parameters corresponding to the selected segments are seamlessly stitched together and used to produce an intermediate video representation in which the lower half of the face is rendered with a parametric face model. Finally, a recurrent video generation network transforms this representation to a photorealistic video that matches the edited transcript. We demonstrate a large variety of edits, such as the addition, removal, and alteration of words, as well as convincing language translation and full sentence synthesis.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.01524](http://arxiv.org/abs/1906.01524)

##### PDF
[http://arxiv.org/pdf/1906.01524](http://arxiv.org/pdf/1906.01524)

