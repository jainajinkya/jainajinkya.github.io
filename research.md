---
layout: page
title: Research
permalink: /research/
---
<div class="toc">
  <ul class="texts"> 
      <li class="text-title">
      <b> Efficient Hierarchical Robot Motion Planning Under Uncertainty and Hybrid Dynamics </b>
      	<p> Noisy observations coupled with nonlinear dynamics pose one of the biggest challenges in robot motion planning. By decomposing the nonlinear dynamics into a discrete set of local dynamics models, hybrid dynamics provide a natural way to model nonlinear dynamics, especially in systems with sudden "jumps" in the dynamics, due to factors such as contacts. We propose a hierarchical POMDP planner that develops locally optimal motion plans for hybrid dynamics models. The hierarchical planner first develops a high-level motion plan to sequence the local dynamics models to be visited. The high-level plan is then converted into a detailed cost-optimized continuous state plan. This hierarchical planning approach results in a decomposition of the POMDP planning problem into smaller sub-parts that can be solved with significantly lower computational costs. The ability to sequence the visitation of local dynamics models also provides a powerful way to leverage the hybrid dynamics to reduce state uncertainty. We evaluate the proposed planner for two navigation and localization tasks in simulated domains, as well as an assembly task with a real robotic manipulator. <a href="https://arxiv.org/abs/1802.04205" target="_blank"> [arXiv preprint]</a> </p> 
      	
     	<iframe width="560" height="315" src="https://www.youtube.com/embed/rT3CUle7Lsk" frameborder="0" allowfullscreen></iframe> <br> <br><br><br>
    </li>

<!--     <li class="text-title">
      <b> Robot manipulation planning under uncertainty using hybrid dynamics </b>
      	<p> The difficulty of many robot manipulation tasks stems from stochasticity and partial observability coupled with highly nonlinear dynamics. However, much of the nonlinearity in manipulation tasks can be explained by sudden changes in contact or articulated state. This fact allows the dynamics to be naturally factored into a discrete set of simpler models combined together as a hybrid dynamics model. To leverage these hybrid dynamics for efficient planning under uncertainty, we introduce a novel POMDP planner that computes and stabilizes around trajectories in a hybrid belief space. We evaluate the proposed planner in both a simulated navigation domain, as well as an assembly task with a real robotic manipulator. Experiments on robot doing a partial assembly of Toy airplane from the YCB Dataset <a href="/files/hblqr.pdf" target="_blank"> [manuscript]</a> </p> 
      	
     	<iframe width="560" height="315" src="https://www.youtube.com/embed/IMLakQdTi6c" frameborder="0" allowfullscreen></iframe>
    </li> -->
  </ul>
</div>