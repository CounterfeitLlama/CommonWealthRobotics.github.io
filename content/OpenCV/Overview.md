---
title: Overview
step: 0
layout: post
---

##OpenCV
OpenCV is a tool for object detection using a camera or input file from the computer. There are two essential pieces in this tool: the trainer and detector. Using a database of images of a certain object, OpenCV can train a template to be able to later detect an object using the detector.

##Train Cascade
OpenCV can train an xml file to be able to detect when a certain object is in the camera or supplied video. It uses machine learning in order to train the file. This means that the more images that are supplied, the better the resulting Cascade Classifier will be.

##Cascade Classifier
After training a Cascade Classifier, or by using a supplied xml file, OpenCV can then recognize objects in the screen. These can be combined so that OpenCV can recognize multiple objects at once, or so that it can more accurately detect the same object. Being the programmer, you have the ability to be creative in this stage.