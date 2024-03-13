---
layout: post
category: projects
title: evaluate generative v2a models
---

ttTtRRR (drumroll)

Today I released a very early beta version of a (looong-term) project. Main idea is to provide easy and (semi) automated pipeline to test visual2audio (or anything2audio) models! Basically all that the user needs is to have the ground truth videos and videos where audio was generated with v2a (or any other generative audio) model... and then run the pipeline. It will calculate user configured metrics and visualize the results (◔_◔).

At the moment, the evaluation *pipeline* (¯\_(ツ)_/¯) supports 3 different metrics:

1. Frechet Audio Distance (FAD)
2. Kulback-Leibler Divergence (KLD)
3. Audio-Visual Synchronisation Score

I am planning on to add more metrics and also to improve the pipeline in general. In the mean time, I hope that this pipeline will be useful for someone else too! You can find the project [here](https://github.com/ilpoviertola/eval_generative_v2a_models).

Until next time ♥‿♥ xoxo
