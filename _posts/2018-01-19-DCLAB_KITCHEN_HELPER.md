---
layout: post
title:  "Kitchen's Helper"
date:   2018-01-19
excerpt: "We implemented an automatic cutting machine, which can cut the target into demanded pieces equally."
feature_fig: <figure><img src="https://kevin71104.github.io/assets/img/DCLAB_Kitchen/product.jpg"></figure>
project: true
tag:
- Course Work
- Verilog
- Field Programmable Gate Array
comments: true
---

<figure><img src="https://kevin71104.github.io/assets/img/DCLAB_Kitchen/product.jpg"></figure>

<center>
	<a href="https://kevin71104.github.io/assets/document/DCLAB_Kitchen_Helper.pdf" target="_blank" class="btn btn-danger">
		<span style="font-size: 120%;">
			Technical Report
		</span>
	</a>
	&nbsp;
	<a href="https://www.youtube.com/watch?v=INd2CLuVJFw&feature=youtu.be" target="_blank" class="btn btn-warning">
		<span style="font-size: 120%;">
			YouTube
		</span>
	</a>
	&nbsp;
	<a href="https://github.com/kevin71104/DCLab/tree/master/final/src" class="btn btn-success">
		<span style="font-size: 120%;">
			GitHub Code
		</span>
	</a>
</center>

<figure><img src="https://kevin71104.github.io/assets/img/DCLAB_Kitchen/Architecture.png"></figure>

In this project, we implement a kitchen's helper, which can cut the food in the equal pieces.
In addition, the number of pieces can be chosen as 2, 4, or 8.
We write the Verilog code to control **Field Programmable Gate Array (FPGA)** and use supersonic element (HC-SR04) to detect the distance.
In order to conduct "CUT" and "MOVE", we use the stepper motor (28ybj-48) and driver (L298).
This work is chosen as the top-3 project in the course.