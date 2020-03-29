---
layout: post
title: Choice keras or pytorch?
---

In this month,  I join a competition of underwater object detection. During the winter vacation, I learned object detection's knowledge and classic models, such as 
YOLO, Faster R-CNN and SSD. So I want to participate a competition to use the knowledge which I learned.

In this competition and three competitions in last summer vacation, I always use keras to finish the task(tensorflow is backend). In the image classification task, 
using keras is not bad. But in the object detection, the models of out of the box in keras is too little to use. I use three models of SSD, Faster R-CNN and YOLOv3. But 
only YOLOv3 is work, other two models which have the highest stars in github is terrible. The SSD in the highest stars repository is not support to train on own dataset. 
The Faster R-CNN in the highest stars repository has four base models, but everyone has error in training. And the YOLOv3, although it's work, the result in this 
competition is too bad. Even if I read most of code in this repository, I still don't know the reason of this problem.

In the QQ group of the competition, some high score players share the mmdetection. I find this repository in the github which based on pytorch . It's so amazing that 
this repository integrate almost all models of object detection, even the data augment in this. According to high score players, using this repository can get very good 
score. Looking back at keras, no repository can do that. I also can't implement all code of one model by myself for one competition. This is not allowed in terms of 
time and cost. I search some classic models in other fields based on pytorch in github, finding that they were very successful to implement model and their stars 
generally higher than the same type of keras repository. Even some models just has pytroch implement, not has keras.

So that, I just want to learn pytorch after this competition. Most of models and trick, even the newest of them, all of them basically use pytorch to implement. And the 
results are also very well. More about of this competition and my personal learning after competition, I will writing in the next blog. Of course, if you want to 
implement your model in the industrial field, using tensorflow even keras is better than pytorch. Tensorflow is better than pytorch. But pytorch has fast development 
in this way, so it's just a matter of time to catch up with tensorflow. If you want to implement your model in the academic research or competition, must to learing 
pytorch, now!
