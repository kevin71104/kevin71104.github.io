---
layout: post
title:  "Different Handover Policies in Different Environments"
date:   2017-08-25
excerpt: "We implement a <b>user-friendly GUI</b> based on MATLAB to discuss the performances of four possible handover policy under different environment."
project: true
feature_fig: <figure><img src="https://kevin71104.github.io/assets/img/WMC_Handover/GUI.JPG"></figure>
tag:
- Course Work
- Wireless Communication
- Handover
comments: true
mathjax: true
---

<figure><img src="https://kevin71104.github.io/assets/img/WMC_Handover/GUI.JPG"></figure>

<center>
	<a href="https://kevin71104.github.io/assets/document/WMC_Handover.pdf" target="_blank" class="btn btn-danger">
		<span style="font-size: 120%;">
			Technical Report
		</span>
	</a>
	&nbsp;
	<a href="https://github.com/kevin71104/WMC/tree/master/WMC%20FINAL" class="btn btn-success">
		<span style="font-size: 120%;">
			GitHub Code
		</span>
	</a>
</center>

In this project, we want to discuss the performance of different **handover policies** in different environments.
Therefore, we consider four handover policies, including as Eager, Lazy, Eager Threshold (ET) and Relative Threshold (RT). 
In the Eager mode, MS will switch to new BS if another BS has better SINR than the current one. 
In the Lazy mode, MS will switch to new BS if another BS has had better SINR than the current one for continuous 5 cycles. 
In the ET mode, MS will switch to new BS if another BS has better SINR than the current one and SINR is larger than a speciﬁc threshold. 
In the RT mode, MS will switch to new BS if another BS has larger SINR than the current one by a speciﬁc threshold.
We consider two path-loss model, namely,  smooth transition and two-ray-ground, and we also consider shadowing and fading.
Moreover, to better observe the influence of handover policies, we implement a user-friendly GUI, 
which provides an interface for people to modify parameters and observe the result easily.