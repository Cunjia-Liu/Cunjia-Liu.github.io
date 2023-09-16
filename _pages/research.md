---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
redirect_from:
  - /research
---
{% include base_path %}


My research sits at the interface between control engineering, informatics and robotics, which focuses on developing innovative algorithms and systematic solutions to Robotics and Autonomous Systems (RAS). With an inspiration to advance their applications in different domains, there is a diverse range of sectors that my research can contribute to, ranging from transport, agriculture, energy to defence and security.

## Control for vehicle/robot dynamics 
![image](/images/dobc_diagram.png){: style="float: left; margin-right: 0.5em;"} 
We aim to advance the control design for vehicles and robots with complicated dynamics and to improve their robustness and performance in adverse conditions. We developed various disturbance observer based control (DOBC) techniques to compensate uncertainties and disturbances, and continue to integrate such a function with other methods like MPC to achieve safety-critial control in dynamic environments.   

<details>
	<summary> <b> Applications: UAV flight control </b> <sup>(click me)</sup> </summary> 
	<h3> DOBC design for UAV path-folloiwng </h3>
	{% include youtubePlayer.html id="M_qy1iH7u3M" %}
	<h3> DOBC + MPC for helicopter control  </h3> 
	{% include youtubePlayer.html id="TXJjf8RHnIk" %}
	
</details>  

## Planning for autonomous missions
![image](/images/IPP_diagram.png){: style="float: left; margin-right: 0.5em;"} 
Having worked on different path planning solutions for UAVs, my recent focus is on informative path planning for robotic environment monitoring and information gathering. It can be regarded as a paradigm of “planning for data”, where robotic systems under information-driven control are able to take appropriate actions to interrogate the environment for more informative data or useful feedback. We have had a lot of success in applying this kind of framework in autonomous search of unknown chemical, biological, radiological (CBR) releases.  

<details>
	<summary> <b> Robotic CBR responses </b> <sup>(click me)</sup> </summary>
	<h3> Information path planning for robotic source term estimation </h3>
	{% include youtubePlayer.html id="NdbED6RTZyI" %}
	<h3> Autonomous airbrone search in cluttered environments </h3>
	{% include youtubePlayer.html id="_Sou67QbVqo" %} 
 	[Matlab code for working examples](https://github.com/lcj-1234/AutoSTE) 
	
</details>  

<!---
<details>
	<summary> <b> Coverage path planning </b> <sup>(click me)</sup> </summary>
	<h3> <a href="https://onlinelibrary.wiley.com/doi/full/10.1002/rob.21928"> Decomposition‐based mission planning for fixed‐wing UAVs surveying in wind </a> </h3>
	<img src="/images/cpp_remotesensing.png" width="50%">
	
</details>
-->

## Perception and information fusion 

By the virtue of the Bayesian framework, we are interested in fusing different sensor information and 'world knowledge' to achieve two primary goals: 1) to establish a better situational awareness for robotic systems operated in a dynamic environment, inlcuding tracking other objects in the environment; 2) to find an effective way to represent and understand environmental features, such as mapping crop disease or chemical gas distributions, based on the data collected by robotic systems.


<details>
	<summary> <b> Robotic environment mapping </b> <sup>(click me)</sup> </summary>
	<h3> <a href="https://ieeexplore.ieee.org/abstract/document/10057445"> Structurally aware 3D gas distribution mapping using belief propagation </a>  </h3>
	{% include youtubePlayer.html id="crAJd4afW8c" %}
</details>  


<details>
	<summary> <b> Particle filtering with state constraints </b> <sup>(click me)</sup> </summary>
	<p> <a href="https://ieeexplore.ieee.org/abstract/document/7742936"> An auxiliary particle filtering algorithm with inequality constraints </a></p>
	<p> <a href="https://ieeexplore.ieee.org/abstract/document/8676363"> Particle filtering with soft state constraints for target tracking </a></p>
	<img src="/images/CAPF.png" width="50%">
</details>  







