---
layout: post
title: tensorflow install with anaconda
date: 2017-02-21 11:22
comments: true
external-url:
categories: software-engineering
---

> firstly using Anaconda instead of pip to install tensorflow1.0, beacuse Anaconda is more flexiable and easier to control version update. pip in different python version is hard to manage because of 
system PATH, and Anaconda is more conveient in this aspect.(using pip command to update pip version is still a problem)

> secondly, installing tensorflow-gpu need install cuda, cudann, [see this](https://www.tensorflow.org/install/install_linux#installing_with_anaconda). Then install with anaconda can follow this [instruction](https://www.tensorflow.org/install/install_linux#TF_PYTHON_URL)


this maybe occur some bug as follows:

1. Conda command not found: maybe zshrc enviroment problem, see [this website](http://stackoverflow.com/questions/18675907/how-to-run-conda)

2. if you using anaconda python3.6 but tensorflow noly support python3.5, [see this instruction](http://stackoverflow.com/questions/42266094/tensorflow-1-0-windows-64-bit-anaconda-4-3-0-error) 

sucessful install tensorflow in cpu but failes install in tensorflow-gpu, and this part is to be done
