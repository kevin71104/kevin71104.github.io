---
layout: post
title:  "An Analysis of Operations Modification in Deep Neural Network in Hardware Perspective"
date:   2018-01-19
excerpt: "We analyze the tradeoff between hardware resource requirement and top-1 accuracy of state-of-the-art CNN models."
project: true
feature_fig: <figure class="half"><img src="https://kevin71104.github.io/assets/img/AVLSI_CNN/con_1.png" class="img-disappear"> <img src="https://kevin71104.github.io/assets/img/AVLSI_CNN/con_2.png"></figure>
tag:
- Course Work
- Very-Large-Scale Integration
- Convolutional Neural Network
- Hardware Analysis
comments: true
mathjax: true
---

<figure class="half">
	<img src="https://kevin71104.github.io/assets/img/AVLSI_CNN/con_1.png" class="img-disappear"> 
	<img src="https://kevin71104.github.io/assets/img/AVLSI_CNN/con_2.png">
</figure>

<center>
	<a href="https://kevin71104.github.io/assets/document/AVLSI_CNN.pdf" target="_blank" class="btn btn-danger">
		<span style="font-size: 120%;">
			Technical Report
		</span>
	</a>
	&nbsp;
	<a href="https://github.com/kevin71104/AVLSI/tree/master/AVLSI%20final/code" class="btn btn-success">
		<span style="font-size: 120%;">
			GitHub Code
		</span>
	</a>
</center>

As the convolutional neural network (CNN) achieving better classification performance in figures such as ImageNet data set,
many state-of-the-art architectures have been proposed, including **AlexNet**, **GoogleNet**, **ResNet** and **Xception**.
However, these models only focus on classification accuracy, and thus the strcucture goes deeper and deeper, 
which is a great budden for hardware implementation.
In this project, we survey and review several famous CNN architectures and conduct experiments to test the power consumption of each architecture.
With these experiments, we summarize the top-1 accuracy, top-5 accuracy, the number of parameters, GFLOPs, power and inference time in a table
and draw some charts to analyze the advantages and drawbacks of these architectures.
Finally, we survey some hardware-friendly design, which is helpful if we want to implement these CNN architectures by hardware.