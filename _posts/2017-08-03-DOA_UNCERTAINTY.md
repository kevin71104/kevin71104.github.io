---
layout: post
title:  "DOA Estimation Under Uncertainty"
date:   2017-08-03
excerpt: "<strong>K.-C. Hsu</strong> and J.-F. Kiang, ''DOA Estimation of Quasi-Stationary Signals Using a Partly-Calibrated Uniform Linear Array
with Fewer Sensors than Sources,'' <i>Progress In Electromagnetics Research M (PIER M)</i>, vol. 63, pp. 185-193, 2018."
feature_fig: <figure><img src="https://kevin71104.github.io/assets/img/DOA_UNCERTAINTY/Estimation_Compare.jpg"></figure>
research: true
tag:
- Research
- Direction-of-Arrival Estimation
- Uncertainty
- Khatri-Rao Subspace
comments: true
---
<center>
<figure>
	<img src="{{site.url}}/assets/img/DOA_UNCERTAINTY/flow_chart.jpg">
</figure>
</center>

<center>
	<a href="https://kevin71104.github.io/assets/document/DOA_UNCERTAINTY.pdf" target="_blank" class="btn btn-danger">
		<span style="font-size: 120%;">
		PDF Publication
		</span>
	</a>
	&nbsp;
	<a href="http://www.jpier.org/PIERM/pier.php?paper=17080306" target="_blank" class="btn btn-warning">
		<span style="font-size: 120%;">
		PIER M Publication
		</span>
	</a>
</center>

When we use antenna array to estimate the **direction-of-arrival (DOA)** of received signals, 
the uncertainty of gain and phase in the antennas will degrade the estimation accuracy.
However, the calibration is time-consuming, and it is infeasible to calibrate frequently.
To evaluate DOA under partly-calibrated antenna array is an inevitable problem.
With an uniform linear array of N antennas, previous work can accurately estimate (2N-2) sensors.
In this work, we utilize the special structure of the covariance matrix from received signals to estimate the uncertainty of gain and phase.
Then, we vectorize covariance matrices of several observed time frames and stack them into a matrix, 
so the Khatri-Rao subspace is formulated.
Finally, we apply traditional **MUltiple SIgnal Classification (MUSIC)** on above-mentioned matrix, 
and thus the estimated DOAs have smaller error.

The contribution of this work comes in two aspects:
- The gain and phase uncertainty in partly-calibrated ULA are correctly estimated
- The DOFs of ULA with N sensors are increased from (2N-2) to (2N-1)

<center>
<figure>
	<img src="https://kevin71104.github.io/assets/img/DOA_UNCERTAINTY/Estimation_Compare.jpg">
</figure>
</center>

<p class="double_underline">PUBLICATION:</p>
**K.-C. Hsu** and J.-F. Kiang, 
''DOA estimation of quasi-stationary signals using a partly-calibrated uniform linear array
with fewer sensors than sources,'' 
<i>Progress In Electromagnetics Research M (PIER M)</i>, vol. 63, pp. 185-193, 2018.


