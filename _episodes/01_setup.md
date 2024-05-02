---
title: "Installing Docker"
teaching: 5
exercises: 0
questions:
 - How do I install Docker?
objectives:
 - Install Docker
keypoints:
 - You should now be able to run `docker run hello-world`
---

The following link has instructions for how to install Docker.
We will be using the command line for this work shop so try to install Docker Engine (not Docker Desktop), this is easiest on Linux or WSL.

[Docker install instructions](https://docs.docker.com/engine/install/)

To test if you have installed docker correctly you can run

~~~
sudo docker run hello-world
~~~

It is also easier to follow [these extra steps](https://docs.docker.com/engine/install/linux-postinstall/) so that you don't have to use sudo every time you run a docker command.
If you have followed the extra steps correctly you should be able to run

~~~
docker run hello-world
~~~
