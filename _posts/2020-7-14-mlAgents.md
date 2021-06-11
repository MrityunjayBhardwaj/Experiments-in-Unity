---
layout: post 
title : Unity's ML Agents
tags  : [ML,AI, Reinforcement Learning, RL, Unity, Agents]
title-seprator: "|"
categories: Reinforcement Learning
permalink: /:categories/:title.html
mathjax: true
author: Mrityunjay
height: 0px
img: /posts_imgs/mlAgents/teaser/mlAgents.png
viz: mlAgents/index.html
---
<br>

Although I've been following the work of Arthur Juliani and unity team for a long time, I never actually got around using ML Agents package untill now.

In a Nutshell, The ML-Agents Toolkit Low Level API is a Python API for controlling the simulation loop of an environment or game built with Unity. This API is used by the training algorithms inside the ML-Agent Toolkit, but you can also write your own program using this API.

I started by playing with the roller ball project comes with the package and then eventually stumble upon some tutorials you can use to create custom environments for you agent, you can even use [tensorboard](https://www.tensorflow.org/tensorboard) to track you experiments! 

<div style="margin: 0 auto; text-align: center">
    <img src="{{site.url}}/assets/img/posts_imgs/mlAgents/body/1.png"  width="800px" />
</div>

then i finally created a custom environment using WRLD3d and the results looks promising..

<div style="margin: 0 auto; text-align: center">
    <img src="{{site.url}}/assets/img/posts_imgs/mlAgents/body/2.png"  width="800px" />
</div>

Currently, I am working On some more Environments which i'll share, once its presentable... till then, happy learning!
