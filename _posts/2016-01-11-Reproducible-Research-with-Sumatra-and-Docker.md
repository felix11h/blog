---
layout: post
title: A reproducible research environment with Sumatra and Docker
---

Docker is a [great candidate] #make this a proper citation? for creating a computational research environment that allows for easy replication of computations and results. [Sumatra] is . How well do these 

Fist we need a docker image . Here's an image it's build from the following dockerfile:



You can either

sudo docker run

or build the image yourself by creating a directory containing the dockerfile above (named "dockerfile") and execute

sudo docker build

Don't forget the dot at the end of the line! Now you can create container with image you created via

Here's an explanation of the different flags set in the run command:




Within the container


[great candidate]:<http://arxiv.org/abs/1410.0846>
[Sumatra]: