---
layout: post
title:  "Pipelined MIPS CPU"
date:   2017-06-15
excerpt: "We implemented the pipelined MIPS CPU, which supported mult/div instruction and conducted branch prediction."
feature_fig: <figure><img src="https://kevin71104.github.io/assets/img/CA_Pipeline_CPU/architecture.JPG"></figure>
project: true
tag:
- Course Work
- Very-Large-Scale Integration
- Computer Architecture
- Verilog
comments: true
---
<figure><img src="https://kevin71104.github.io/assets/img/CA_Pipeline_CPU/architecture.JPG"></figure>

<center>
	<a href="https://kevin71104.github.io/assets/document/CA_Pipelined_CPU.pdf" target="_blank" class="btn btn-danger">
		<span style="font-size: 120%;">
			Technical Report
		</span>
	</a>
</center>

In this project, we implemented the MIPS CPU with pipeline architecture by Verilog code 
and managed to overcome data hazard, lw-use hazard, structural hazard, and control hazard.
Besides, we extended the basic function by considering branch prediction, L1/L2 cache, and support of multiplication and division.
We compared the performance of different implementations of branch prediction, namely, one-bit or two-bit.
In addition, we discussed the advantages that L1/L2 cache brings about.
In the final presentation, our work was awarded the second prize.
