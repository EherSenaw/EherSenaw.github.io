---
layout: post
title: "Post: Connect docker container with pycharm"
categories:
  - post
tags:
  - post
  - pycharm
  - docker
---
**About this section**: 

Follow these simple steps to connect docker conatiner with pycharm.


## Environment
* Ubuntu 18.04
  > Doesn't **NEED** to be **18.04**. Other versions would fit well.
* PyCharm **Professional**
  > **Only** professional has 'docker' options aviailable.
* Docker
  > Pretend already installed.

## Steps
0. If there is any project already opened, close project. Therefore you can get this window.

    ![image-0](http://ehersenaw.github.io/images/2020-12-28-post-pycharm+docker/0.png)

1. Customize - All settings...
  - Python Interpreter
    - Click **Options** menu on the left of 'Python Interpreter: ...'
    - Click **Add...**
    
      ![image-1-1](http://ehersenaw.github.io/images/2020-12-28-post-pycharm+docker/1-1.png)

      ![image-1-2](http://ehersenaw.github.io/images/2020-12-28-post-pycharm+docker/1-2.png)

      ![image-1-3](http://ehersenaw.github.io/images/2020-12-28-post-pycharm+docker/1-3.png)

  - Add Python Interpreter
    - **Docker**
    - Click **New...** on the right of **Server: ...**

      ![image-1-3](http://ehersenaw.github.io/images/2020-12-28-post-pycharm+docker/1-4.png)

  - Docker
    - Name as you want. I'll do as *Python_docker_ex*
    - Select **Connect to Docker daemon with:** as **Unix Socket**
    - Click **OK**

      ![image-1-5](http://ehersenaw.github.io/images/2020-12-28-post-pycharm+docker/1-5.png)

  - Now back to **Add Python Interpreter - Docker**
    - Select **Image name** of docker image that you want to use on pycharm. (In this example, I will use *pytorch/pytorch*)
    - Click **OK**
    
      ![image-1-6](http://ehersenaw.github.io/images/2020-12-28-post-pycharm+docker/1-6.png)

2. Open Project
  - **Run - Edit Configurations...**
    - Select Python interpreter as **Remote Python Docker** of docker image that you want to use. (I will use *pytorch/pytorch*'s python)
    - Click **Apply** and **OK**
    
      ![image-2-1](http://ehersenaw.github.io/images/2020-12-28-post-pycharm+docker/2-1.png)

  - **RUN!**
    - **Run** your *main.py*(or whatever you want to try)
    
      ![image-2-2](http://ehersenaw.github.io/images/2020-12-28-post-pycharm+docker/2-2.png)
    
  - **Done!**

      ![image-2-3](http://ehersenaw.github.io/images/2020-12-28-post-pycharm+docker/2-3.png)

># Contact: onow7353@gmail.com
